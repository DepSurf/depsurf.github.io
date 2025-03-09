# Function: <code>set_dumpable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581019424,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1709",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:setup_new_exec"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019424,
      "name": "set_dumpable.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581025680,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581185191,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1858",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:setup_new_exec"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178704,
      "name": "set_dumpable.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581184800,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581262460,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1886",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:setup_new_exec"
      ],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255824,
      "name": "set_dumpable.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071581262096,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581311168,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1918",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311168,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581451184,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1922",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451184,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581611104,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1957",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611104,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581697456,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1957",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697456,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815563,
      "name": "set_dumpable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581815104,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887696,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887696,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114928,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2068",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114928,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161424,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2054",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161424,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582185536,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2054",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582185536,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502896,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2056",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502896,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583026304,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2083",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026304,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590400,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2093",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590400,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583806640,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2100",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583806640,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012832,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:2121",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012832,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493363616,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493363616,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226952200,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226952200,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286910208,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286910208,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273084988,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273084988,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581856432,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856432,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794032,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794032,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847744,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847744,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void set_dumpable(struct mm_struct * mm, int value)
```

```json
{
  "name": "set_dumpable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917264,
      "name": "set_dumpable",
      "external": true,
      "loc": "fs/exec.c:1960",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/cred.c:commit_creds",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917264,
      "name": "set_dumpable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
