# Function: <code>klp_apply_section_relocs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:288",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_init_object_loaded",
        "kernel/module.c:apply_relocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136475,
      "name": "klp_apply_section_relocs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580133168,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:288",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_init_object_loaded",
        "kernel/module.c:apply_relocations"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309610,
      "name": "klp_apply_section_relocs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580111392,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:287",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_init_object_loaded",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591251659,
      "name": "klp_apply_section_relocs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580115200,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:287",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_init_object_loaded",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592147502,
      "name": "klp_apply_section_relocs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580257456,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:287",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_init_object_loaded",
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593920201,
      "name": "klp_apply_section_relocs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580426704,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667440,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:294",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_init_object_loaded",
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667440,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746176,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:332",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746176,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
```

```json
{
  "name": "klp_apply_section_relocs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831248,
      "name": "klp_apply_section_relocs",
      "external": true,
      "loc": "kernel/livepatch/core.c:332",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831248,
      "name": "klp_apply_section_relocs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int klp_apply_section_relocs(struct module * pmod, Elf64_Shdr * sechdrs, const char * shstrtab, const char * strtab, unsigned int symndx, unsigned int secndx, const char * objname)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
