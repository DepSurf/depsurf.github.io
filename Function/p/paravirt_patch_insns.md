# Function: <code>paravirt_patch_insns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258004,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:181",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258080,
      "name": "paravirt_patch_insns",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579257419,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:166",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257488,
      "name": "paravirt_patch_insns",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270939,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:166",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271008,
      "name": "paravirt_patch_insns",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267488,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:166",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_patch",
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267488,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579284448,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:176",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284448,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579295904,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:182",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295904,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int paravirt_patch_insns(void * insnbuf, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320448,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:161",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:native_patch",
        "arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320448,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335680,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:149",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335680,
      "name": "paravirt_patch_insns",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579339888,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:149",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339888,
      "name": "paravirt_patch_insns",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369312,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:150",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369312,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368320,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:150",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368320,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335792,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:149",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335792,
      "name": "paravirt_patch_insns",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579269088,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:149",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269088,
      "name": "paravirt_patch_insns",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335712,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:149",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335712,
      "name": "paravirt_patch_insns",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```

```json
{
  "name": "paravirt_patch_insns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579344096,
      "name": "paravirt_patch_insns",
      "external": true,
      "loc": "arch/x86/kernel/paravirt.c:149",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/paravirt.c:paravirt_patch_default",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:native_patch",
        "arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344096,
      "name": "paravirt_patch_insns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * insn_buff</code>
</li>
<li>
<b>Param removed. </b>
<code>void * insnbuf</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int paravirt_patch_insns(void * insn_buff, unsigned int len, const char * start, const char * end)
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
