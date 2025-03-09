# Function: <code>do_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t do_sysctl(int * args_name, int nlen, void * oldval, size_t oldlen, void * newval, size_t newlen)
```

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409440,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1401",
      "file": "kernel/sysctl_binary.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:SyS_sysctl",
        "kernel/sysctl_binary.c:compat_SyS_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409440,
      "name": "do_sysctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 990
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
ssize_t do_sysctl(int * args_name, int nlen, void * oldval, size_t oldlen, void * newval, size_t newlen)
```

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421552,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1392",
      "file": "kernel/sysctl_binary.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:compat_SyS_sysctl",
        "kernel/sysctl_binary.c:SyS_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421552,
      "name": "do_sysctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 954
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
ssize_t do_sysctl(int * args_name, int nlen, void * oldval, size_t oldlen, void * newval, size_t newlen)
```

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441904,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1392",
      "file": "kernel/sysctl_binary.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:compat_SyS_sysctl",
        "kernel/sysctl_binary.c:SyS_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441904,
      "name": "do_sysctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 954
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431309,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1392",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:compat_SyS_sysctl",
        "kernel/sysctl_binary.c:SyS_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:compat_SyS_sysctl",
        "kernel/sysctl_binary.c:SyS_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430032,
      "name": "do_sysctl.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 922
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579459645,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1400",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:compat_SyS_sysctl",
        "kernel/sysctl_binary.c:SyS_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:compat_SyS_sysctl",
        "kernel/sysctl_binary.c:SyS_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458384,
      "name": "do_sysctl.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472220,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1382",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471168,
      "name": "do_sysctl.isra.1.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071579472365,
      "name": "do_sysctl.isra.1.part.2.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505884,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504832,
      "name": "do_sysctl.isra.1.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071579506029,
      "name": "do_sysctl.isra.1.part.2.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524908,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523872,
      "name": "do_sysctl.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579525055,
      "name": "do_sysctl.isra.0.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550988,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549952,
      "name": "do_sysctl.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579551135,
      "name": "do_sysctl.isra.0.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579582700,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:78",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581888,
      "name": "do_sysctl.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579583070,
      "name": "do_sysctl.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490702600,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__arm64_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__arm64_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__arm64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490700296,
      "name": "do_sysctl.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224766980,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__se_sys_sysctl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283526996,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__se_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__se_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__se_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__se_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__se_sys_sysctl",
        "kernel/sysctl_binary.c:__se_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283526128,
      "name": "do_sysctl.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271428684,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:__se_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271428684,
      "name": "do_sysctl.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527330,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525616,
      "name": "do_sysctl.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
    },
    {
      "addr": 18446744071579527455,
      "name": "do_sysctl.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579456130,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454416,
      "name": "do_sysctl.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
    },
    {
      "addr": 18446744071579456255,
      "name": "do_sysctl.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524572,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523536,
      "name": "do_sysctl.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579524719,
      "name": "do_sysctl.isra.0.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579557532,
      "name": "do_sysctl",
      "external": false,
      "loc": "kernel/sysctl_binary.c:1383",
      "file": "kernel/sysctl_binary.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ],
      "caller_func": [
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__x32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_compat_sys_sysctl",
        "kernel/sysctl_binary.c:__ia32_sys_sysctl",
        "kernel/sysctl_binary.c:__x64_sys_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556496,
      "name": "do_sysctl.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579557679,
      "name": "do_sysctl.isra.0.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t do_sysctl(int * args_name, int nlen, void * oldval, size_t oldlen, void * newval, size_t newlen)
```
</details>
</li>
</ul>
