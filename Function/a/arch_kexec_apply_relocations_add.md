# Function: <code>arch_kexec_apply_relocations_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(const Elf64_Ehdr * ehdr, Elf64_Shdr * sechdrs, unsigned int relsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222208,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:408",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222208,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 728
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
int arch_kexec_apply_relocations_add(const Elf64_Ehdr * ehdr, Elf64_Shdr * sechdrs, unsigned int relsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222576,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:410",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222576,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 729
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
int arch_kexec_apply_relocations_add(const Elf64_Ehdr * ehdr, Elf64_Shdr * sechdrs, unsigned int relsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579234736,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:411",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234736,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 729
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
int arch_kexec_apply_relocations_add(const Elf64_Ehdr * ehdr, Elf64_Shdr * sechdrs, unsigned int relsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232400,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:429",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232400,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 708
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
int arch_kexec_apply_relocations_add(const Elf64_Ehdr * ehdr, Elf64_Shdr * sechdrs, unsigned int relsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248080,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:431",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248080,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 714
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131980,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:396",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261024,
      "name": "arch_kexec_apply_relocations_add.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071579260352,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 569
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179292,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:396",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284784,
      "name": "arch_kexec_apply_relocations_add.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071579284016,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 660
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225262,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:494",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299949,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579299120,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273534,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:494",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305501,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579304672,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342462,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:427",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_apply_relocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335021,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579334192,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591314932,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:427",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_apply_relocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591262725,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579335776,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591257109,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:427",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591205307,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579338480,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592160514,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:398",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592077403,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579393856,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:398",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593843913,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579460336,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549600,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:398",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549600,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579564752,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:387",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564752,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592288,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:384",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592288,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtab)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491513688,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "kernel/kexec_file.c:120",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491513688,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtab)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284479676,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "kernel/kexec_file.c:120",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284479676,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 64
    }
  ]
}
```
</details>
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580242334,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:494",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301309,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579300480,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189886,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:494",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236749,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579235920,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233598,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:494",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302509,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579301680,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```

```json
{
  "name": "arch_kexec_apply_relocations_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286574,
      "name": "arch_kexec_apply_relocations_add",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:494",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311341,
      "name": "arch_kexec_apply_relocations_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071579310512,
      "name": "arch_kexec_apply_relocations_add",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 648
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct purgatory_info * pi</code>
</li>
<li>
<b>Param added. </b>
<code>Elf64_Shdr * section</code>
</li>
<li>
<b>Param added. </b>
<code>const Elf64_Shdr * symtabsec</code>
</li>
<li>
<b>Param removed. </b>
<code>const Elf64_Ehdr * ehdr</code>
</li>
<li>
<b>Param removed. </b>
<code>Elf64_Shdr * sechdrs</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int relsec</code> ➡️ <code>const Elf64_Shdr * relsec</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const Elf64_Shdr * symtab</code>
</li>
<li>
<b>Param removed. </b>
<code>const Elf64_Shdr * symtabsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const Elf64_Shdr * symtab</code>
</li>
<li>
<b>Param removed. </b>
<code>const Elf64_Shdr * symtabsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info * pi, Elf64_Shdr * section, const Elf64_Shdr * relsec, const Elf64_Shdr * symtabsec)
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
