# Function: <code>would_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581017936,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1136",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:setup_new_exec"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017936,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581185221,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1283",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:setup_new_exec"
      ],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176368,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253344,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1297",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253344,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302784,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1323",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302784,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581442656,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1315",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442656,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601248,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1319",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601248,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687264,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1323",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687264,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805440,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1324",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805440,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581877904,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581877904,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582103680,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1483",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582103680,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150288,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1412",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150288,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175024,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1408",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175024,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492208,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1410",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492208,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015840,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1415",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015840,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583579808,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1414",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579808,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794912,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1417",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794912,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001008,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1435",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:begin_new_exec",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001008,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493354368,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493354368,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226943116,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__do_execve_file",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226943116,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286897184,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286897184,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273077496,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__do_execve_file",
        "fs/binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273077496,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846640,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846640,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784304,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784304,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837952,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837952,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void would_dump(struct linux_binprm * bprm, struct file * file)
```

```json
{
  "name": "would_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907328,
      "name": "would_dump",
      "external": true,
      "loc": "fs/exec.c:1325",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907328,
      "name": "would_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
