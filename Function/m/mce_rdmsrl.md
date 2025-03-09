# Function: <code>mce_rdmsrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125440,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:372",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125440,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125616,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:415",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125616,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579132704,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:440",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132704,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579131840,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:371",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131840,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579146208,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:380",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146208,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156512,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:377",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156512,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579146000,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:375",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146000,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158224,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:392",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158224,
      "name": "mce_rdmsrl",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160720,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:392",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160720,
      "name": "mce_rdmsrl",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180096,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:374",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180096,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591651920,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:395",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591651920,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591595776,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:395",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591595776,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592767632,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:404",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592767632,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594663456,
      "name": "mce_rdmsrl",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:342",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594663456,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596397536,
      "name": "mce_rdmsrl",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:342",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596397536,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596928496,
      "name": "mce_rdmsrl",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:336",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596928496,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597854224,
      "name": "mce_rdmsrl",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:367",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info",
        "arch/x86/kernel/cpu/mce/core.c:mce_gather_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597854224,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579161088,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:392",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161088,
      "name": "mce_rdmsrl",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092608,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:392",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092608,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160640,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:392",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160640,
      "name": "mce_rdmsrl",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 mce_rdmsrl(u32 msr)
```

```json
{
  "name": "mce_rdmsrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579165776,
      "name": "mce_rdmsrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:392",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux",
        "arch/x86/kernel/cpu/mce/core.c:mce_read_aux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165776,
      "name": "mce_rdmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
u64 mce_rdmsrl(u32 msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 mce_rdmsrl(u32 msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 mce_rdmsrl(u32 msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 mce_rdmsrl(u32 msr)
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
