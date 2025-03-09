# Function: <code>security_file_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244368,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:759",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244368,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582463088,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:781",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463088,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555552,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:802",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555552,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582642592,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1414",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582642592,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582796992,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1372",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:SyS_ioctl",
        "fs/compat_ioctl.c:compat_SyS_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582796992,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994368,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:898",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994368,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583106048,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1434",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583106048,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292208,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1453",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292208,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397248,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397248,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724880,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1663",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:ksys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724880,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845072,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1665",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845072,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870912,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1715",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870912,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234688,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1723",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234688,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840320,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1728",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840320,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541712,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1769",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541712,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585772368,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:2766",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__do_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772368,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586020656,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:2826",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__ia32_sys_ioctl",
        "fs/ioctl.c:__x64_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020656,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495149368,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495149368,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228537040,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228537040,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289073168,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__se_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289073168,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274397048,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274397048,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365984,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365984,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303088,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303088,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349760,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349760,
      "name": "security_file_ioctl",
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
int security_file_ioctl(struct file * file, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "security_file_ioctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444944,
      "name": "security_file_ioctl",
      "external": true,
      "loc": "security/security.c:1493",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:ksys_ioctl",
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl",
        "fs/compat_ioctl.c:do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444944,
      "name": "security_file_ioctl",
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
