# Function: <code>final_note</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "final_note",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579944404,
      "name": "final_note",
      "external": false,
      "loc": "kernel/kexec_core.c:968",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "final_note",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579975236,
      "name": "final_note",
      "external": false,
      "loc": "kernel/kexec_core.c:1015",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "final_note",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580005716,
      "name": "final_note",
      "external": false,
      "loc": "kernel/kexec_core.c:1017",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012592,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:313",
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
      "addr": 18446744071580012592,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059424,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:314",
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
      "addr": 18446744071580059424,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580116656,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:314",
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
      "addr": 18446744071580116656,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163648,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:314",
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
      "addr": 18446744071580163648,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209648,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446744071580209648,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257984,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446744071580257984,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580326594,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/crash_core.c:update_vmcoreinfo_note"
      ],
      "caller_func": [
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326624,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580312082,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:314",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/crash_core.c:update_vmcoreinfo_note"
      ],
      "caller_func": [
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312112,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580315570,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:314",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/crash_core.c:update_vmcoreinfo_note"
      ],
      "caller_func": [
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315600,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580469106,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:326",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/crash_core.c:update_vmcoreinfo_note"
      ],
      "caller_func": [
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469136,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580662736,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:322",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662736,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932752,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:334",
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
      "addr": 18446744071580932752,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019152,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:334",
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
      "addr": 18446744071581019152,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117040,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:653",
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
      "addr": 18446744071581117040,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491500720,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446603336491500720,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void final_note(Elf32_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225482260,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 3225482260,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284460272,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_build_cpu_notes",
        "kernel/crash_core.c:update_vmcoreinfo_note",
        "kernel/kexec_core.c:crash_save_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284460272,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271942522,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/crash_core.c:update_vmcoreinfo_note"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271942578,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580226784,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446744071580226784,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580174272,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446744071580174272,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218256,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446744071580218256,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void final_note(Elf64_Word * buf)
```

```json
{
  "name": "final_note",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271024,
      "name": "final_note",
      "external": true,
      "loc": "kernel/crash_core.c:312",
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
      "addr": 18446744071580271024,
      "name": "final_note",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void final_note(Elf64_Word * buf)
```
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
