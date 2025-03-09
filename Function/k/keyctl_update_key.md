# Function: <code>keyctl_update_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196192,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:311",
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
      "addr": 18446744071582196192,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412704,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:311",
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
      "addr": 18446744071582412704,
      "name": "keyctl_update_key",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504896,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:311",
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
      "addr": 18446744071582504896,
      "name": "keyctl_update_key",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586272,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:316",
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
      "addr": 18446744071582586272,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582739376,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:316",
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
      "addr": 18446744071582739376,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939024,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:316",
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
      "addr": 18446744071582939024,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047568,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:316",
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
      "addr": 18446744071583047568,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230736,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446744071583230736,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336512,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446744071583336512,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669968,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071583669968,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583791872,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071583791872,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816048,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071583816048,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179088,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071584179088,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584779344,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071584779344,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476112,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071585476112,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585707568,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071585707568,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585954608,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:325",
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
      "addr": 18446744071585954608,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495080232,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446603336495080232,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228474376,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 3228474376,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288977808,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 13835058055288977808,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274345124,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446743936274345124,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305248,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446744071583305248,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242384,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446744071583242384,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289280,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446744071583289280,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
long int keyctl_update_key(key_serial_t id, const void * _payload, size_t plen)
```

```json
{
  "name": "keyctl_update_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583383888,
      "name": "keyctl_update_key",
      "external": true,
      "loc": "security/keys/keyctl.c:326",
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
      "addr": 18446744071583383888,
      "name": "keyctl_update_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
