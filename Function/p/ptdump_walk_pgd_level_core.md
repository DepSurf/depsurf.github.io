# Function: <code>ptdump_walk_pgd_level_core</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320144,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:375",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320144,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
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
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579335360,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:376",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335360,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1046
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
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329392,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:430",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329392,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
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
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354560,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:478",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354560,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:496",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366016,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
    },
    {
      "addr": 18446744071579368117,
      "name": "ptdump_walk_pgd_level_core.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:523",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393536,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1234
    },
    {
      "addr": 18446744071579395572,
      "name": "ptdump_walk_pgd_level_core.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:518",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409696,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071579410940,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:518",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412880,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071579414136,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441040,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071579443192,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439296,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071591271557,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442080,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071591214316,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506528,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071592089856,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588720,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071593856798,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699312,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071595970443,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713184,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071596488026,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void ptdump_walk_pgd_level_core(struct seq_file * m, struct mm_struct * mm, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:365",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747904,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071597384648,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:518",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408720,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071579409976,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:518",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337296,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
    },
    {
      "addr": 18446744071579339288,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:518",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408640,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071579409896,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```

```json
{
  "name": "ptdump_walk_pgd_level_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptdump_walk_pgd_level_core",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:518",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417504,
      "name": "ptdump_walk_pgd_level_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071579418760,
      "name": "ptdump_walk_pgd_level_core.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dmesg</code>
</li>
</ul>
</details>
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
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, pgd, checkwx, dmesg</code> ➡️ <code>m, mm, pgd, checkwx, dmesg</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ptdump_walk_pgd_level_core(struct seq_file * m, pgd_t * pgd, bool checkwx, bool dmesg)
```
</details>
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
