# Function: <code>kimage_file_alloc_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579955608,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:253",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579985943,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:200",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580016471,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:204",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580023609,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:191",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580070617,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:191",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:264",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126624,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071580132036,
      "name": "kimage_file_alloc_init.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:263",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174032,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 18446744071580179348,
      "name": "kimage_file_alloc_init.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:309",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220000,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
    },
    {
      "addr": 18446744071580225318,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268352,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071580273590,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:292",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338192,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    },
    {
      "addr": 18446744071580342518,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:298",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323408,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
    },
    {
      "addr": 18446744071591314988,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:298",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326688,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
    },
    {
      "addr": 18446744071591257165,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:298",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481200,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
    },
    {
      "addr": 18446744071592160570,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:265",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675440,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
    },
    {
      "addr": 18446744071593933584,
      "name": "kimage_file_alloc_init.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:269",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946256,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
    },
    {
      "addr": 18446744071595999382,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:269",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033168,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071596517517,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581134939,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:273",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491511256,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284476100,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237152,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071580242390,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184704,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071580189942,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228528,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071580233654,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```

```json
{
  "name": "kimage_file_alloc_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kimage_file_alloc_init",
      "external": false,
      "loc": "kernel/kexec_file.c:314",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281392,
      "name": "kimage_file_alloc_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071580286630,
      "name": "kimage_file_alloc_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kimage_file_alloc_init(struct kimage * * rimage, int kernel_fd, int initrd_fd, const char * cmdline_ptr, long unsigned int cmdline_len, long unsigned int flags)
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
