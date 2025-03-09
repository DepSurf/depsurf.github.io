# Function: <code>elf_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364240,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:337",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581376704,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:337",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364240,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071581376704,
      "name": "elf_map.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545408,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:336",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581556880,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:336",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545408,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071581556880,
      "name": "elf_map.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581630784,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:336",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581641856,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:336",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630784,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071581641856,
      "name": "elf_map.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581682400,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:344",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581694736,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:344",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682400,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071581694736,
      "name": "elf_map.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827936,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:349",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581840384,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:349",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827936,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071581840384,
      "name": "elf_map.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004272,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:349",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582018320,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:349",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004272,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071582018320,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092080,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:349",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582106240,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:349",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092080,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071582106240,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254208,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071582267048,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582268256,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582281767,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353872,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071582366438,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582367568,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582380853,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:356",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:356",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643568,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071582653082,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582654816,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071582666119,
      "name": "elf_map.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:360",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:360",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714832,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071591344717,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582725904,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071591344759,
      "name": "elf_map.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:363",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:363",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743824,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071591287471,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582754560,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071591287513,
      "name": "elf_map.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583073424,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:363",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071583081984,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:363",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073424,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071583081984,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:365",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:365",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547408,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071594023547,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583560512,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071594023589,
      "name": "elf_map.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584153984,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:365",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584166384,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:365",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153984,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071584166384,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584381616,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:370",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584394304,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:370",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381616,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071584394304,
      "name": "elf_map.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584599334,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:356",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611692,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:356",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493948584,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336493962808,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493948584,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446603336493962808,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf32_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227412380,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227412380,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287588912,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 13835058055287604480,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287588912,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 13835058055287604480,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273483392,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273483392,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322608,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071582335174,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582336304,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582349589,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260368,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071582272902,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582274032,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582287301,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313088,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071582325654,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582326784,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582340069,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Transformation ❓</summary>

```c
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
```

```json
{
  "name": "elf_map",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 0,
      "name": "elf_map",
      "external": false,
      "loc": "fs/binfmt_elf.c:348",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392320,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071582404913,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582406592,
      "name": "elf_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071582419392,
      "name": "elf_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<b>Param type changed. </b>
<code>struct elf64_phdr * eppnt</code> ➡️ <code>const struct elf64_phdr * eppnt</code>
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
long unsigned int elf_map(struct file * filep, long unsigned int addr, const struct elf64_phdr * eppnt, int prot, int type, long unsigned int total_size)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct elf64_phdr * eppnt</code> ➡️ <code>const struct elf32_phdr * eppnt</code>
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
