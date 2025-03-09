# Function: <code>fill_prstatus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364508,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1403",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581374480,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1403",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374480,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581550701,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1411",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581555472,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1411",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555472,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581635877,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1411",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581640544,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1411",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640544,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581687426,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1469",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581699855,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1469",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581832998,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1483",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581845511,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1483",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582007260,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1495",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582021865,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1495",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582095148,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1495",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582109945,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1495",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582262254,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1498",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582276916,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1498",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582361636,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582375991,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582640368,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1590",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ]
    },
    {
      "addr": 18446744071582657136,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1590",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582640368,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071582657136,
      "name": "fill_prstatus",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582711504,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1498",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ]
    },
    {
      "addr": 18446744071582726880,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1498",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582711504,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071582726880,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582741464,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1501",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755545,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1501",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583068344,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1501",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082457,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1501",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583546392,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1536",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561017,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1536",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147032,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1531",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584163465,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1531",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584374296,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1536",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391365,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1536",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584592633,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1471",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:fill_thread_core_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608469,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1471",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493956636,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493971836,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227419428,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227423664,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf_fdpic.c:1342",
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
      "addr": 3227423664,
      "name": "fill_prstatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287598312,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287613704,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273485298,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582330372,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582344727,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582268132,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582282455,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582320852,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582335207,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fill_prstatus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582400084,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582415016,
      "name": "fill_prstatus",
      "external": false,
      "loc": "fs/binfmt_elf.c:1472",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void fill_prstatus(struct elf_prstatus * prstatus, struct task_struct * p, long int signr)
```
</details>
</li>
</ul>
