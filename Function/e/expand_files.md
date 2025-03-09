# Function: <code>expand_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int expand_files(struct files_struct * files, int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114400,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:210",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:__alloc_fd",
        "fs/file.c:replace_fd",
        "fs/file.c:SyS_dup2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114400,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int expand_files(struct files_struct * files, int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280112,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:211",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280112,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358560,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:211",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358560,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413664,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:197",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413664,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555280,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:198",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:SyS_dup2",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555280,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581712380,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711728,
      "name": "expand_files.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581798892,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798240,
      "name": "expand_files.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917072,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917072,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989456,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989456,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582223488,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582223488,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271232,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:198",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271232,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296608,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:198",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296608,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:198",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615504,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    },
    {
      "addr": 18446744071592230368,
      "name": "expand_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:214",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150112,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071594010339,
      "name": "expand_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:214",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723696,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    },
    {
      "addr": 18446744071596051329,
      "name": "expand_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:214",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940752,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071596573887,
      "name": "expand_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:214",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146352,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071597478425,
      "name": "expand_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493503760,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493503760,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227059640,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227059640,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287064496,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287064496,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273176090,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273176090,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958192,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958192,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581895760,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581895760,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949504,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949504,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int expand_files(struct files_struct * files, unsigned int nr)
```

```json
{
  "name": "expand_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019424,
      "name": "expand_files",
      "external": false,
      "loc": "fs/file.c:193",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:ksys_dup3",
        "fs/file.c:replace_fd",
        "fs/file.c:__alloc_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019424,
      "name": "expand_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr</code> ➡️ <code>unsigned int nr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int expand_files(struct files_struct * files, unsigned int nr)
```
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
