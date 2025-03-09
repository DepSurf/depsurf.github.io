# Function: <code>load_elf_library</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363712,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1108",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581375216,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1108",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363712,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    },
    {
      "addr": 18446744071581375216,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581544864,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1113",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581556128,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1113",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544864,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071581556128,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630240,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1113",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581641104,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1113",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630240,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071581641104,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681840,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1171",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581694032,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1171",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681840,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071581694032,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827344,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1181",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581839472,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1181",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827344,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071581839472,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003680,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1194",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582017728,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1194",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003680,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582017728,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091488,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1194",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582105648,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1194",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091488,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582105648,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253616,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1201",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582267664,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1201",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253616,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582267664,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353280,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582366976,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353280,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582366976,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647824,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1302",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582660800,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1302",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647824,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071582660800,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717808,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1330",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582729728,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1330",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717808,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071582729728,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582746912,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1333",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582758528,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1333",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582746912,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    },
    {
      "addr": 18446744071582758528,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073840,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1333",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583085440,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1333",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073840,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    },
    {
      "addr": 18446744071583085440,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552112,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1368",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583564032,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1368",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552112,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
    },
    {
      "addr": 18446744071583564032,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153312,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1363",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584162784,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1363",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153312,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    },
    {
      "addr": 18446744071584162784,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584380928,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1368",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584390688,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1368",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380928,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071584390688,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Transformation ❓</summary>

```c
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599872,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1319",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1319",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599872,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071584612224,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071597488001,
      "name": "load_elf_library.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493958888,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493973368,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493958888,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    },
    {
      "addr": 18446603336493973368,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227418168,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227418168,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287589776,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287605344,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287589776,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
    },
    {
      "addr": 13835058055287605344,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273491518,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273491518,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582322016,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582335712,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322016,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582335712,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259776,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582273440,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259776,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582273440,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312496,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582326192,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312496,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582326192,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
int load_elf_library(struct file * file)
```

```json
{
  "name": "load_elf_library",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391728,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582406000,
      "name": "load_elf_library",
      "external": false,
      "loc": "fs/binfmt_elf.c:1175",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391728,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071582406000,
      "name": "load_elf_library",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
