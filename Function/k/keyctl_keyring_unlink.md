# Function: <code>keyctl_keyring_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196896,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:516",
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
      "addr": 18446744071582196896,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413488,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:537",
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
      "addr": 18446744071582413488,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582505680,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:537",
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
      "addr": 18446744071582505680,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582587056,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:542",
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
      "addr": 18446744071582587056,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740192,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:542",
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
      "addr": 18446744071582740192,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939856,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:542",
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
      "addr": 18446744071582939856,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048400,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:542",
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
      "addr": 18446744071583048400,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231568,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583231568,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583337344,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583337344,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670800,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583670800,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792704,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583792704,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816896,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583816896,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179936,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071584179936,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780224,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071584780224,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585477072,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071585477072,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585708528,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071585708528,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585955568,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071585955568,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495081136,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446603336495081136,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228475288,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 3228475288,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288979136,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 13835058055288979136,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274345868,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446743936274345868,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306080,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583306080,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243216,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583243216,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290112,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583290112,
      "name": "keyctl_keyring_unlink",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_unlink(key_serial_t id, key_serial_t ringid)
```

```json
{
  "name": "keyctl_keyring_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384720,
      "name": "keyctl_keyring_unlink",
      "external": true,
      "loc": "security/keys/keyctl.c:552",
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
      "addr": 18446744071583384720,
      "name": "keyctl_keyring_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
