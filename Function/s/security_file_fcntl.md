# Function: <code>security_file_fcntl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244720,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244720,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582463440,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:847",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463440,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555904,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:868",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555904,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642944,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1480",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642944,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797392,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1438",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl",
        "fs/fcntl.c:SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797392,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994672,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:964",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994672,
      "name": "security_file_fcntl",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583106352,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1500",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583106352,
      "name": "security_file_fcntl",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292560,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1519",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292560,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397744,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397744,
      "name": "security_file_fcntl",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737200,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1734",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737200,
      "name": "security_file_fcntl",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857536,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1736",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857536,
      "name": "security_file_fcntl",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583883696,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1786",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883696,
      "name": "security_file_fcntl",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584247648,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1794",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584247648,
      "name": "security_file_fcntl",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584856976,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1799",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856976,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560992,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1841",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560992,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585791936,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:2891",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791936,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039984,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:2969",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039984,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495150000,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__arm64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495150000,
      "name": "security_file_fcntl",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228537616,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_sys_fcntl64",
        "fs/fcntl.c:__se_sys_fcntl64",
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228537616,
      "name": "security_file_fcntl",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289074368,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289074368,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274397496,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:__se_sys_fcntl",
        "fs/fcntl.c:__se_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274397496,
      "name": "security_file_fcntl",
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
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583366480,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583366480,
      "name": "security_file_fcntl",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303584,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303584,
      "name": "security_file_fcntl",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350256,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350256,
      "name": "security_file_fcntl",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int security_file_fcntl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_fcntl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445440,
      "name": "security_file_fcntl",
      "external": true,
      "loc": "security/security.c:1558",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:do_compat_fcntl64",
        "fs/fcntl.c:__ia32_sys_fcntl",
        "fs/fcntl.c:__x64_sys_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445440,
      "name": "security_file_fcntl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
