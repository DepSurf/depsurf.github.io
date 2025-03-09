# Function: <code>vm_brk_flags</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934448,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:2955",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934448,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int vm_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034208,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:2981",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034208,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168752,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3023",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168752,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248832,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3069",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248832,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323520,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3075",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323520,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382864,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382864,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579024,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3092",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579024,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624560,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3150",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624560,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581649056,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3121",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649056,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917168,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3107",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917168,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323680,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3107",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323680,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582821984,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3026",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821984,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035568,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3118",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035568,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217152,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3212",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_load",
        "fs/compat_binfmt_elf.c:elf_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217152,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492789800,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492789800,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226605240,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226605240,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286159600,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286159600,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272759976,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272759976,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351712,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351712,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295424,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295424,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342912,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342912,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags)
```

```json
{
  "name": "vm_brk_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406848,
      "name": "vm_brk_flags",
      "external": true,
      "loc": "mm/mmap.c:3081",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vm_brk",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:set_brk",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:set_brk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406848,
      "name": "vm_brk_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int vm_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags)
```
</details>
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
<code>long unsigned int request</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int len</code>
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
