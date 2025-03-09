# Function: <code>elf_core_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371744,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2124",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581383328,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2124",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371744,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2615
    },
    {
      "addr": 18446744071581383328,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2641
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552640,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2132",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581564016,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2132",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552640,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2712
    },
    {
      "addr": 18446744071581564016,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2739
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637824,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2125",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581648736,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2125",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637824,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2593
    },
    {
      "addr": 18446744071581648736,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2625
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689408,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581701968,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689408,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2558
    },
    {
      "addr": 18446744071581701968,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2500
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835056,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2198",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581847680,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2198",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835056,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2556
    },
    {
      "addr": 18446744071581847680,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2499
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582014368,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2212",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582029136,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2212",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014368,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2834
    },
    {
      "addr": 18446744071582029136,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2823
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102320,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2212",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582117200,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2212",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102320,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2814
    },
    {
      "addr": 18446744071582117200,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2780
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2210",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2210",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264336,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2712
    },
    {
      "addr": 18446744071582267111,
      "name": "elf_core_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582279104,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2663
    },
    {
      "addr": 18446744071582281830,
      "name": "elf_core_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363728,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582378192,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363728,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2710
    },
    {
      "addr": 18446744071582378192,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2661
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645968,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2304",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582658960,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2304",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645968,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1847
    },
    {
      "addr": 18446744071582658960,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1837
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582716624,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2154",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582728528,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2154",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582716624,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
    },
    {
      "addr": 18446744071582728528,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745536,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2154",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582757152,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2154",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745536,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
    },
    {
      "addr": 18446744071582757152,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072048,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2156",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583084064,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2156",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072048,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
    },
    {
      "addr": 18446744071583084064,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583550624,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2195",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583562752,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2195",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583550624,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
    },
    {
      "addr": 18446744071583562752,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1271
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152000,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2021",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584165088,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2021",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152000,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1284
    },
    {
      "addr": 18446744071584165088,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1271
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584379632,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2026",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584392992,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2026",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584379632,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1279
    },
    {
      "addr": 18446744071584392992,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1283
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597824,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:1961",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584610176,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:1961",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597824,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1367
    },
    {
      "addr": 18446744071584610176,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493959744,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493974248,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493959744,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2208
    },
    {
      "addr": 18446603336493974248,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227421028,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227421028,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2508
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287600640,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287616032,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287600640,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2908
    },
    {
      "addr": 13835058055287616032,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2892
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273487068,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273487068,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1740
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582332464,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582346928,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332464,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2710
    },
    {
      "addr": 18446744071582346928,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2661
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270192,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582284640,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270192,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2710
    },
    {
      "addr": 18446744071582284640,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2661
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582322944,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582337408,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322944,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2710
    },
    {
      "addr": 18446744071582337408,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2661
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
int elf_core_dump(struct coredump_params * cprm)
```

```json
{
  "name": "elf_core_dump",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402208,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582416736,
      "name": "elf_core_dump",
      "external": false,
      "loc": "fs/binfmt_elf.c:2184",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402208,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2705
    },
    {
      "addr": 18446744071582416736,
      "name": "elf_core_dump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2656
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
