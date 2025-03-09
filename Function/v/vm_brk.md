# Function: <code>vm_brk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707872,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:2822",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:set_brk",
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707872,
      "name": "vm_brk",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824416,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:2756",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824416,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889920,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:2909",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889920,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934672,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:2975",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934672,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034432,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3001",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034432,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169040,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3050",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169040,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249120,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3096",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249120,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323824,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3102",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323824,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581383168,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383168,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579328,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3119",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579328,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624928,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3177",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624928,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649424,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3148",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649424,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917552,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3134",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917552,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324064,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3134",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324064,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582822608,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3073",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582822608,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583036192,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3165",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036192,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492790072,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492790072,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226605524,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226605524,
      "name": "vm_brk",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286160032,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286160032,
      "name": "vm_brk",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272760170,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272760170,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352016,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352016,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295728,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295728,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343216,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343216,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int vm_brk(long unsigned int addr, long unsigned int len)
```

```json
{
  "name": "vm_brk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407152,
      "name": "vm_brk",
      "external": true,
      "loc": "mm/mmap.c:3108",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_library",
        "fs/compat_binfmt_elf.c:load_elf_library"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407152,
      "name": "vm_brk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len)
```
</details>
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
