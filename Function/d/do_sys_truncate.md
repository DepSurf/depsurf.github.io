# Function: <code>do_sys_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981776,
      "name": "do_sys_truncate",
      "external": false,
      "loc": "fs/open.c:124",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_truncate",
        "fs/open.c:compat_SyS_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981776,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136944,
      "name": "do_sys_truncate",
      "external": false,
      "loc": "fs/open.c:124",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:compat_SyS_truncate",
        "fs/open.c:SyS_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136944,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212112,
      "name": "do_sys_truncate",
      "external": false,
      "loc": "fs/open.c:135",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:compat_SyS_truncate",
        "fs/open.c:SyS_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212112,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "do_sys_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581261944,
      "name": "do_sys_truncate",
      "external": false,
      "loc": "fs/open.c:135",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:compat_SyS_truncate",
        "fs/open.c:SyS_truncate"
      ],
      "caller_func": [
        "fs/open.c:compat_SyS_truncate",
        "fs/open.c:SyS_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258736,
      "name": "do_sys_truncate.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "do_sys_truncate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581401080,
      "name": "do_sys_truncate",
      "external": false,
      "loc": "fs/open.c:135",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:compat_SyS_truncate",
        "fs/open.c:SyS_truncate"
      ],
      "caller_func": [
        "fs/open.c:compat_SyS_truncate",
        "fs/open.c:SyS_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397872,
      "name": "do_sys_truncate.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581554704,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:135",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554384,
      "name": "do_sys_truncate.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581555872,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581640352,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:124",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640032,
      "name": "do_sys_truncate.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581641360,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581757037,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756720,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581758064,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829245,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828928,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581830272,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582050573,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:122",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050256,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071582051008,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582100157,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:122",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099840,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071582100880,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582125837,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:123",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125520,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071582125872,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441757,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:122",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x64_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__x64_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441440,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071582442512,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960128,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:122",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960128,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518544,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:122",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518544,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733984,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:123",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733984,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583934827,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:123",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935040,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493292176,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__arm64_compat_sys_truncate",
        "fs/open.c:__arm64_sys_truncate"
      ],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_truncate64",
        "fs/open.c:__arm64_compat_sys_truncate",
        "fs/open.c:__arm64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493291872,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446603336493293552,
      "name": "do_sys_truncate",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226897316,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__se_sys_truncate64",
        "fs/open.c:__se_sys_truncate"
      ],
      "caller_func": [
        "fs/open.c:__se_sys_truncate64",
        "fs/open.c:__se_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226895508,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 3226896660,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286830176,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__se_compat_sys_truncate",
        "fs/open.c:__se_sys_truncate"
      ],
      "caller_func": [
        "arch/powerpc/kernel/sys_ppc32.c:compat_sys_truncate64",
        "fs/open.c:__se_compat_sys_truncate",
        "fs/open.c:__se_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286829840,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 13835058055286831584,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273038750,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__se_sys_truncate"
      ],
      "caller_func": [
        "fs/open.c:__se_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273036338,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446743936273038666,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581797981,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797664,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581799008,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581735645,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581735328,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581736672,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581789293,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788976,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581790320,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
```

```json
{
  "name": "do_sys_truncate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581858429,
      "name": "do_sys_truncate",
      "external": true,
      "loc": "fs/open.c:125",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64",
        "fs/open.c:__x32_compat_sys_truncate",
        "fs/open.c:__ia32_compat_sys_truncate",
        "fs/open.c:__ia32_sys_truncate",
        "fs/open.c:__x64_sys_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858112,
      "name": "do_sys_truncate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581859456,
      "name": "do_sys_truncate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long int do_sys_truncate(const char * pathname, loff_t length)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int do_sys_truncate(const char * pathname, loff_t length)
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
