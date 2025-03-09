# Function: <code>total_mapping_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582128865,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:373",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581374368,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:373",
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
      "addr": 18446744071582128865,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071581374368,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582346926,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:372",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581555360,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:372",
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
      "addr": 18446744071582346926,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071581555360,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438181,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:372",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581640432,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:372",
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
      "addr": 18446744071582438181,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071581640432,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691966,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:380",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581693552,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:380",
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
      "addr": 18446744071581691966,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071581693552,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837612,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:385",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581839136,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:385",
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
      "addr": 18446744071581837612,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071581839136,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003152,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:390",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582017216,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:390",
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
      "addr": 18446744071582003152,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071582017216,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int total_mapping_size(struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090960,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:390",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582105136,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:390",
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
      "addr": 18446744071582090960,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071582105136,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253072,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582267136,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446744071582253072,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071582267136,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352768,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582366480,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446744071582352768,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071582366480,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640208,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:395",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582653136,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:395",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640208,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071582653136,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582711376,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:399",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582723248,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:399",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582711376,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071582723248,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740704,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:402",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582752144,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:402",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582740704,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071582752144,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067616,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:402",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071583079072,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:402",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067616,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071583079072,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583556051,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:404",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568000,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:404",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584157528,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:404",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169981,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:404",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584385165,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:409",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584397947,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:409",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584603318,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:449",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616118,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:449",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary"
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493947936,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336493962200,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446603336493947936,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446603336493962200,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
long unsigned int total_mapping_size(const struct elf32_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227411004,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 3227411004,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287588064,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 13835058055287603600,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 13835058055287588064,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 13835058055287603600,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273482998,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446743936273482998,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321504,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582335216,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446744071582321504,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071582335216,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259264,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582272944,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446744071582259264,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071582272944,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311984,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582325696,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446744071582311984,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071582325696,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
```

```json
{
  "name": "total_mapping_size",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391216,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582404960,
      "name": "total_mapping_size",
      "external": false,
      "loc": "fs/binfmt_elf.c:389",
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
      "addr": 18446744071582391216,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071582404960,
      "name": "total_mapping_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
<code>struct elf64_phdr * cmds</code> ➡️ <code>const struct elf64_phdr * cmds</code>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
long unsigned int total_mapping_size(const struct elf64_phdr * cmds, int nr)
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
<code>const struct elf64_phdr * cmds</code> ➡️ <code>const struct elf32_phdr * cmds</code>
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
