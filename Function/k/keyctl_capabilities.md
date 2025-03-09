# Function: <code>keyctl_capabilities</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583236993,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl",
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230432,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583238016,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583342817,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl",
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334208,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583343840,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583678104,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1849",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669664,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583678448,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583799608,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1849",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791152,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583799952,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583823777,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1849",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815328,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071583824144,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584186817,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1849",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176848,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071584187184,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786928,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1849",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786928,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484064,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1849",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484064,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585715552,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1854",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715552,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962672,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1853",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl",
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962672,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495087580,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__arm64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__arm64_sys_keyctl",
        "security/keys/compat.c:__arm64_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495079592,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446603336495087656,
      "name": "keyctl_capabilities",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228481540,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228472980,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 3228481008,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288987744,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl",
        "security/keys/compat.c:__se_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288977216,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 13835058055288987904,
      "name": "keyctl_capabilities",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274350940,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274344108,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446743936274350324,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583311553,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl",
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302944,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583312576,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583248657,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl",
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240080,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583249680,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583295585,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl",
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286976,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583296608,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```

```json
{
  "name": "keyctl_capabilities",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583390225,
      "name": "keyctl_capabilities",
      "external": true,
      "loc": "security/keys/keyctl.c:1694",
      "file": "security/keys/keyctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl",
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381584,
      "name": "keyctl_capabilities.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071583391248,
      "name": "keyctl_capabilities",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int keyctl_capabilities(unsigned char * _buffer, size_t buflen)
```
</details>
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
