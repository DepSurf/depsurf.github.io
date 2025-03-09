# Function: <code>load_elf_phdrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363568,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:400",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581374896,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:400",
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
      "addr": 18446744071581363568,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071581374896,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544720,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:399",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581555888,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:399",
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
      "addr": 18446744071581544720,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071581555888,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630096,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:399",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581640960,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:399",
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
      "addr": 18446744071581630096,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071581640960,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681696,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:407",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581693888,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:407",
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
      "addr": 18446744071581681696,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581693888,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827168,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:412",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581840208,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:412",
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
      "addr": 18446744071581827168,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071581840208,
      "name": "load_elf_phdrs.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003504,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:417",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582017552,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:417",
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
      "addr": 18446744071582003504,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582017552,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
struct elf64_phdr * load_elf_phdrs(struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091312,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:417",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582105472,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:417",
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
      "addr": 18446744071582091312,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582105472,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253440,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582267488,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446744071582253440,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582267488,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353104,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582366800,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446744071582353104,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582366800,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644528,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:433",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582656448,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:433",
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
      "addr": 18446744071582644528,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071582656448,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715152,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:457",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582726192,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:457",
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
      "addr": 18446744071582715152,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071582726192,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582744064,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:460",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582754800,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:460",
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
      "addr": 18446744071582744064,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071582754800,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073648,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:460",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071583082208,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:460",
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
      "addr": 18446744071583073648,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071583082208,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551920,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:461",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071583560768,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:461",
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
      "addr": 18446744071583551920,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583560768,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151056,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:461",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584162576,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:461",
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
      "addr": 18446744071584151056,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071584162576,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378688,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:466",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584390480,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:466",
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
      "addr": 18446744071584378688,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071584390480,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596832,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:506",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584608208,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:506",
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
      "addr": 18446744071584596832,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071584608208,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493948352,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336493962584,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446603336493948352,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446603336493962584,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct elf32_phdr * load_elf_phdrs(const struct elf32_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227412068,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227412068,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287588640,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 13835058055287604192,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 13835058055287588640,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 13835058055287604192,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273483178,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273483178,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321840,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582335536,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446744071582321840,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582335536,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259600,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582273264,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446744071582259600,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582273264,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312320,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582326016,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446744071582312320,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582326016,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate ❓</summary>

```c
struct elf64_phdr * load_elf_phdrs(const struct elf64_hdr * elf_ex, struct file * elf_file)
```

```json
{
  "name": "load_elf_phdrs",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391552,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582405824,
      "name": "load_elf_phdrs",
      "external": false,
      "loc": "fs/binfmt_elf.c:416",
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
      "addr": 18446744071582391552,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582405824,
      "name": "load_elf_phdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
<code>struct elf64_hdr * elf_ex</code> ➡️ <code>const struct elf64_hdr * elf_ex</code>
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
<code>const struct elf64_hdr * elf_ex</code> ➡️ <code>const struct elf32_hdr * elf_ex</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct elf64_phdr *</code> ➡️ <code>struct elf32_phdr *</code>
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
