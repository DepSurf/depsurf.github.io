# Function: <code>kimage_crash_copy_vmcoreinfo</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015904,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:485",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015904,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062992,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:495",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062992,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:495",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123323,
      "name": "kimage_crash_copy_vmcoreinfo.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580120160,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170459,
      "name": "kimage_crash_copy_vmcoreinfo.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580167168,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:498",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216379,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580213040,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264779,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580261440,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333867,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580331520,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:499",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591314828,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580316992,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257005,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580320464,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:501",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592160369,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580475408,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:501",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593933468,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580669264,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580939584,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:501",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939584,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581026624,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:502",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026624,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124832,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:490",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124832,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491504280,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491504280,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225485804,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225485804,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284464336,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284464336,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233579,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580230240,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181131,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580177728,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225051,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580221712,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```

```json
{
  "name": "kimage_crash_copy_vmcoreinfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_crash_copy_vmcoreinfo",
      "external": true,
      "loc": "kernel/kexec_core.c:500",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277819,
      "name": "kimage_crash_copy_vmcoreinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580274528,
      "name": "kimage_crash_copy_vmcoreinfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kimage_crash_copy_vmcoreinfo(struct kimage * image)
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
