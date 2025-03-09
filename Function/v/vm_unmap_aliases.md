# Function: <code>vm_unmap_aliases</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580733568,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1040",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580733568,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852432,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1064",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852432,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580923440,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1035",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923440,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580967776,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1086",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967776,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581069424,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1084",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069424,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581210944,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1071",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210944,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294656,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1071",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294656,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581374232,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1714",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373712,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581435451,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434960,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581646724,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1821",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "security/apparmor/match.c:unpack_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634768,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581693092,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1803",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "security/apparmor/match.c:unpack_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680944,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715828,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:2073",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703184,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581988078,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:2125",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975072,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410243,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:2143",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "security/apparmor/match.c:unpack_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397408,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582917139,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:2205",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "security/apparmor/match.c:unpack_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903952,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120576,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:2324",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120576,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303472,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:2324",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303472,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492838716,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/arm64/mm/pageattr.c:change_memory_common",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492838120,
      "name": "vm_unmap_aliases",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226642340,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226641812,
      "name": "vm_unmap_aliases",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286226672,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/powerpc/mm/mem.c:arch_remove_memory",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286226192,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272791370,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272791024,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404299,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403808,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581346811,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346320,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395499,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395008,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void vm_unmap_aliases()
```

```json
{
  "name": "vm_unmap_aliases",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459432,
      "name": "vm_unmap_aliases",
      "external": true,
      "loc": "mm/vmalloc.c:1722",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "security/apparmor/match.c:aa_dfa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458960,
      "name": "vm_unmap_aliases",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
