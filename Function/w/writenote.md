# Function: <code>writenote</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581365360,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1341",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071581376512,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1341",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365360,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581376512,
      "name": "writenote",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545648,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1349",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071581556688,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1349",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545648,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581556688,
      "name": "writenote",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581631008,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1349",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071581641664,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1349",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631008,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581641664,
      "name": "writenote",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681504,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1407",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071581693696,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1407",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681504,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581693696,
      "name": "writenote",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826976,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1421",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071581839280,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1421",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826976,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581839280,
      "name": "writenote",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003312,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1433",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582017360,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1433",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003312,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582017360,
      "name": "writenote",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091120,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1433",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582105280,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1433",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091120,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582105280,
      "name": "writenote",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253248,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1440",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582267296,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1440",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253248,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582267296,
      "name": "writenote",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352912,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582366608,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352912,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582366608,
      "name": "writenote",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641696,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1532",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info"
      ]
    },
    {
      "addr": 18446744071582654256,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1532",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641696,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582654256,
      "name": "writenote",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712912,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1440",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info",
        "fs/binfmt_elf.c:write_note_info"
      ]
    },
    {
      "addr": 18446744071582723936,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1440",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info",
        "fs/compat_binfmt_elf.c:write_note_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712912,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582723936,
      "name": "writenote",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742160,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1443",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582752832,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1443",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742160,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582752832,
      "name": "writenote",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069040,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1443",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071583079728,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1443",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069040,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071583079728,
      "name": "writenote",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547184,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1478",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071583558128,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1478",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547184,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071583558128,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147840,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1473",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071584159328,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1473",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147840,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584159328,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584375104,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1478",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071584386880,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1478",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375104,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584386880,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593456,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1413",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071584604768,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1413",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593456,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584604768,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493948136,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446603336493962368,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493948136,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446603336493962368,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227411824,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 3227424760,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf_fdpic.c:1278",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump",
        "fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227411824,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 3227424760,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287588336,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 13835058055287603888,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287588336,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 13835058055287603888,
      "name": "writenote",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273483832,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273483832,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321648,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582335344,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321648,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582335344,
      "name": "writenote",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259408,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582273072,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259408,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582273072,
      "name": "writenote",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312128,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582325824,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312128,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582325824,
      "name": "writenote",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate ❓</summary>

```c
int writenote(struct memelfnote * men, struct coredump_params * cprm)
```

```json
{
  "name": "writenote",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391360,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ]
    },
    {
      "addr": 18446744071582405632,
      "name": "writenote",
      "external": false,
      "loc": "fs/binfmt_elf.c:1414",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391360,
      "name": "writenote",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071582405632,
      "name": "writenote",
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
