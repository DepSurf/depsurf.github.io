# Function: <code>create_elf_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129122,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:151",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582130444,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:151",
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
      "addr": 18446744071582129122,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1322
    },
    {
      "addr": 18446744071582130444,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1317
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347120,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:150",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582348423,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:150",
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
      "addr": 18446744071582347120,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
    },
    {
      "addr": 18446744071582348423,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1327
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438375,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:150",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582439799,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:150",
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
      "addr": 18446744071582438375,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
    },
    {
      "addr": 18446744071582439799,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1340
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692173,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:160",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581704468,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:160",
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
      "addr": 18446744071581692173,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1366
    },
    {
      "addr": 18446744071581704468,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1431
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837819,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:165",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071581850179,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:165",
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
      "addr": 18446744071581837819,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1307
    },
    {
      "addr": 18446744071581850179,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1353
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004672,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:165",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582018720,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:165",
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
      "addr": 18446744071582004672,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2403
    },
    {
      "addr": 18446744071582018720,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2968
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092480,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:165",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582106640,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:165",
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
      "addr": 18446744071582092480,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2496
    },
    {
      "addr": 18446744071582106640,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3123
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254576,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582268608,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446744071582254576,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2468
    },
    {
      "addr": 18446744071582268608,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3044
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354240,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582367920,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446744071582354240,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
    },
    {
      "addr": 18446744071582367920,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2851
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642256,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:171",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582655104,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:171",
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
      "addr": 18446744071582642256,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
    },
    {
      "addr": 18446744071582655104,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1333
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713472,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:172",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582724496,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:172",
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
      "addr": 18446744071582713472,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1358
    },
    {
      "addr": 18446744071582724496,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1401
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742464,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:172",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582753136,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:172",
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
      "addr": 18446744071582742464,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071582753136,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1411
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069344,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:172",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071583080032,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:172",
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
      "addr": 18446744071583069344,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
    },
    {
      "addr": 18446744071583080032,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547824,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:174",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071583558496,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:174",
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
      "addr": 18446744071583547824,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1399
    },
    {
      "addr": 18446744071583558496,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584149088,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:174",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584160480,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:174",
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
      "addr": 18446744071584149088,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
    },
    {
      "addr": 18446744071584160480,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376576,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584388256,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:175",
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
      "addr": 18446744071584376576,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
    },
    {
      "addr": 18446744071584388256,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
int create_elf_tables(struct linux_binprm * bprm, const struct elf64_hdr * exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594768,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:156",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071584605984,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:156",
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
      "addr": 18446744071584594768,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
    },
    {
      "addr": 18446744071584605984,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493949704,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446603336493964776,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446603336493949704,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2808
    },
    {
      "addr": 18446603336493964776,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
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
int create_elf_tables(struct linux_binprm * bprm, struct elf32_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227412764,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227412764,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1640
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287590576,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 13835058055287606176,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 13835058055287590576,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2508
    },
    {
      "addr": 13835058055287606176,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2496
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273483986,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273483986,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582322976,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582336656,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446744071582322976,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
    },
    {
      "addr": 18446744071582336656,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2851
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260736,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582274384,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446744071582260736,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
    },
    {
      "addr": 18446744071582274384,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2851
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313456,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582327136,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446744071582313456,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
    },
    {
      "addr": 18446744071582327136,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2851
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
int create_elf_tables(struct linux_binprm * bprm, struct elf64_hdr * exec, long unsigned int load_addr, long unsigned int interp_load_addr)
```

```json
{
  "name": "create_elf_tables",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392688,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    },
    {
      "addr": 18446744071582406944,
      "name": "create_elf_tables",
      "external": false,
      "loc": "fs/binfmt_elf.c:164",
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
      "addr": 18446744071582392688,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2303
    },
    {
      "addr": 18446744071582406944,
      "name": "create_elf_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2851
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int e_entry</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct elf64_hdr * exec</code> ➡️ <code>const struct elf64_hdr * exec</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int phdr_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int load_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>bprm, exec, load_addr, interp_load_addr, e_entry</code> ➡️ <code>bprm, exec, interp_load_addr, e_entry, phdr_addr</code>
</li>
</ul>
</details>
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
<code>struct elf64_hdr * exec</code> ➡️ <code>struct elf32_hdr * exec</code>
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
