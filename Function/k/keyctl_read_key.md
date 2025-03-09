# Function: <code>keyctl_read_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582197888,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:721",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl",
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197888,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582414544,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:749",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl",
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582414544,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582506736,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:749",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl",
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582506736,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582588096,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:754",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl",
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588096,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741248,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:754",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl",
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741248,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940944,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:754",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071582940944,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583049488,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:754",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583049488,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232864,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583232864,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583338688,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583338688,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672208,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071583672208,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794112,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071583794112,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583818288,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071583818288,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181328,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071584181328,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781696,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071584781696,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585478608,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071585478608,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585710048,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071585710048,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585957088,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:825",
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
      "addr": 18446744071585957088,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495082448,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__arm64_sys_keyctl",
        "security/keys/compat.c:__arm64_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495082448,
      "name": "keyctl_read_key",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228476660,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228476660,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288980960,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl",
        "security/keys/compat.c:__se_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288980960,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274346944,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274346944,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307424,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583307424,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244560,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583244560,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291456,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583291456,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
long int keyctl_read_key(key_serial_t keyid, char * buffer, size_t buflen)
```

```json
{
  "name": "keyctl_read_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386064,
      "name": "keyctl_read_key",
      "external": true,
      "loc": "security/keys/keyctl.c:810",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071583386064,
      "name": "keyctl_read_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
