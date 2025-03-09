# Function: <code>copy_strings_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020464,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:561",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020464,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581182128,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:566",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182128,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581259344,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:571",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259344,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581308432,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:597",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308432,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448288,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:597",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448288,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606080,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:601",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606080,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691360,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:604",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691360,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809472,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809472,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882064,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882064,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153312,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:657",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153312,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177360,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:649",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177360,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494832,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:649",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494832,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020496,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:654",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020496,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585904,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:650",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585904,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803088,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:655",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803088,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009296,
      "name": "copy_strings_kernel",
      "external": false,
      "loc": "fs/exec.c:656",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009296,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493357896,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493357896,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226946640,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__do_execve_file",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226946640,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286903520,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286903520,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273083448,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file"
      ],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273079798,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850800,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850800,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788464,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788464,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842112,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842112,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_strings_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911696,
      "name": "copy_strings_kernel",
      "external": true,
      "loc": "fs/exec.c:605",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911696,
      "name": "copy_strings_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int copy_strings_kernel(int argc, const const char * * __argv, struct linux_binprm * bprm)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int copy_strings_kernel(int argc, const const char * * argv, struct linux_binprm * bprm)
```
</details>
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
