# Function: <code>keyctl_keyring_move</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231728,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583231728,
      "name": "keyctl_keyring_move",
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583337504,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583337504,
      "name": "keyctl_keyring_move",
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670976,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583670976,
      "name": "keyctl_keyring_move",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792880,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583792880,
      "name": "keyctl_keyring_move",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817072,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583817072,
      "name": "keyctl_keyring_move",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180112,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071584180112,
      "name": "keyctl_keyring_move",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780400,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071584780400,
      "name": "keyctl_keyring_move",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585477264,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071585477264,
      "name": "keyctl_keyring_move",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585708720,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071585708720,
      "name": "keyctl_keyring_move",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585955760,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071585955760,
      "name": "keyctl_keyring_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495081320,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446603336495081320,
      "name": "keyctl_keyring_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228475452,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 3228475452,
      "name": "keyctl_keyring_move",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288979424,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 13835058055288979424,
      "name": "keyctl_keyring_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274346036,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446743936274346036,
      "name": "keyctl_keyring_move",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306240,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583306240,
      "name": "keyctl_keyring_move",
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243376,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583243376,
      "name": "keyctl_keyring_move",
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290272,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583290272,
      "name": "keyctl_keyring_move",
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
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
```

```json
{
  "name": "keyctl_keyring_move",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384880,
      "name": "keyctl_keyring_move",
      "external": true,
      "loc": "security/keys/keyctl.c:595",
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
      "addr": 18446744071583384880,
      "name": "keyctl_keyring_move",
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int keyctl_keyring_move(key_serial_t id, key_serial_t from_ringid, key_serial_t to_ringid, unsigned int flags)
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
