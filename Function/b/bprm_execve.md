# Function: <code>bprm_execve</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582156752,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1796",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:do_execveat_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156752,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    },
    {
      "addr": 18446744071582157088,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582180896,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1796",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180896,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071582181440,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582498352,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1798",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498352,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071582498896,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583023760,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1803",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023760,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071583024304,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583587616,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1808",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583587616,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071583588176,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583799680,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1811",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799680,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    },
    {
      "addr": 18446744071583800288,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bprm_execve(struct linux_binprm * bprm)
```

```json
{
  "name": "bprm_execve",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002112,
      "name": "bprm_execve",
      "external": false,
      "loc": "fs/exec.c:1853",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002112,
      "name": "bprm_execve.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071584002704,
      "name": "bprm_execve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int bprm_execve(struct linux_binprm * bprm, int fd, struct filename * filename, int flags)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int fd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct filename * filename</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
</ul>
