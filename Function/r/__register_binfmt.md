# Function: <code>__register_binfmt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581018416,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:76",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018416,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581176848,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:77",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176848,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581253968,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:77",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253968,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581303392,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:82",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303392,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440800,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:82",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440800,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599488,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:82",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599488,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685472,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:82",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685472,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815544,
      "name": "__register_binfmt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581803664,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581878912,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878912,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102480,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:82",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102480,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149120,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:85",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149120,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173920,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:85",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173920,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491136,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:85",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491136,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013296,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:85",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013296,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576592,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:85",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576592,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792688,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:86",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792688,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998768,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:87",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998768,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493352568,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493352568,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226941208,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/binfmt_elf_fdpic.c:init_elf_fdpic_binfmt",
        "fs/binfmt_flat.c:init_flat_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226941208,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286894560,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286894560,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273076060,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/binfmt_flat.c:init_flat_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273076060,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581847648,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847648,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581785312,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785312,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581838960,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838960,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __register_binfmt(struct linux_binfmt * fmt, int insert)
```

```json
{
  "name": "__register_binfmt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908336,
      "name": "__register_binfmt",
      "external": true,
      "loc": "fs/exec.c:83",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:init_script_binfmt",
        "fs/binfmt_elf.c:init_elf_binfmt",
        "fs/compat_binfmt_elf.c:init_compat_elf_binfmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908336,
      "name": "__register_binfmt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
