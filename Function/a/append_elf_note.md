# Function: <code>append_elf_note</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 * append_elf_note(u32 * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944144,
      "name": "append_elf_note",
      "external": false,
      "loc": "kernel/kexec_core.c:950",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944144,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
u32 * append_elf_note(u32 * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974992,
      "name": "append_elf_note",
      "external": false,
      "loc": "kernel/kexec_core.c:997",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974992,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
u32 * append_elf_note(u32 * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005472,
      "name": "append_elf_note",
      "external": false,
      "loc": "kernel/kexec_core.c:999",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005472,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012464,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:296",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012464,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059296,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:297",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059296,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580116512,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:297",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116512,
      "name": "append_elf_note",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163504,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:297",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163504,
      "name": "append_elf_note",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209504,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209504,
      "name": "append_elf_note",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257840,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257840,
      "name": "append_elf_note",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580326400,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326400,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311888,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:297",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311888,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315376,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:297",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315376,
      "name": "append_elf_note",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580468912,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:309",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468912,
      "name": "append_elf_note",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662576,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:305",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662576,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932576,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:317",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932576,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581018976,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:317",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018976,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116864,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:636",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116864,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491500568,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491500568,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
Elf32_Word * append_elf_note(Elf32_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225482136,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225482136,
      "name": "append_elf_note",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284460064,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/fadump.c:fadump_regs_to_elf_notes",
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284460064,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271942320,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271942320,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226640,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580226640,
      "name": "append_elf_note",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580174128,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174128,
      "name": "append_elf_note",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218112,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218112,
      "name": "append_elf_note",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
Elf64_Word * append_elf_note(Elf64_Word * buf, char * name, unsigned int type, void * data, size_t data_len)
```

```json
{
  "name": "append_elf_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270880,
      "name": "append_elf_note",
      "external": true,
      "loc": "kernel/crash_core.c:295",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270880,
      "name": "append_elf_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<b>Param type changed. </b>
<code>u32 * buf</code> ➡️ <code>Elf64_Word * buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32 *</code> ➡️ <code>Elf64_Word *</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>Elf64_Word * buf</code> ➡️ <code>Elf32_Word * buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>Elf64_Word *</code> ➡️ <code>Elf32_Word *</code>
</li>
</ul>
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
