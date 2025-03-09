# Function: <code>apply_relocate_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241056,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:139",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241056,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240560,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:140",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_write_object_relocations",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240560,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253008,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:140",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253008,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248752,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:140",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248752,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579265456,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:141",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265456,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:141",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277280,
      "name": "apply_relocate_add.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579276640,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:141",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301264,
      "name": "apply_relocate_add.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579300528,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:129",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317872,
      "name": "apply_relocate_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579317152,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:129",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321904,
      "name": "apply_relocate_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579321184,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350656,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:220",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_apply_section_relocs",
        "kernel/module.c:apply_relocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350656,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350496,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:221",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_apply_section_relocs",
        "kernel/module.c:apply_relocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350496,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355136,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:221",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_apply_section_relocs",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355136,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412768,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:222",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_apply_section_relocs",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412768,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479760,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:222",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_apply_section_relocs",
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479760,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572608,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:223",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_apply_section_relocs",
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572608,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584960,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:252",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_write_section_relocs",
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584960,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614752,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:252",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_write_section_relocs",
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614752,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490295504,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/arm64/kernel/module.c:255",
      "file": "arch/arm64/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490295504,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1868
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225468588,
      "name": "apply_relocate_add",
      "external": false,
      "loc": "include/linux/moduleloader.h:71",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282488160,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/powerpc/kernel/module_64.c:522",
      "file": "arch/powerpc/kernel/module_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282488160,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3412
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271353624,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/riscv/kernel/module.c:296",
      "file": "arch/riscv/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271353624,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:129",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317808,
      "name": "apply_relocate_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579317088,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:129",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252400,
      "name": "apply_relocate_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579251680,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:129",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317728,
      "name": "apply_relocate_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579317008,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```

```json
{
  "name": "apply_relocate_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_relocate_add",
      "external": true,
      "loc": "arch/x86/kernel/module.c:129",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326016,
      "name": "apply_relocate_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579325296,
      "name": "apply_relocate_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int apply_relocate_add(Elf64_Shdr * sechdrs, const char * strtab, unsigned int symindex, unsigned int relsec, struct module * me)
```
</details>
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
