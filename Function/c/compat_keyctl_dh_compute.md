# Function: <code>compat_keyctl_dh_compute</code>

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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601424,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:20",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601424,
      "name": "compat_keyctl_dh_compute",
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754848,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:20",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:compat_SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754848,
      "name": "compat_keyctl_dh_compute",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955136,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:20",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955136,
      "name": "compat_keyctl_dh_compute",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583064704,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:20",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583064704,
      "name": "compat_keyctl_dh_compute",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249328,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249328,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355168,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355168,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690768,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690768,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583812160,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812160,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583836384,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836384,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199376,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199376,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584801904,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801904,
      "name": "compat_keyctl_dh_compute",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585500064,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500064,
      "name": "compat_keyctl_dh_compute",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585731648,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731648,
      "name": "compat_keyctl_dh_compute",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978896,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__do_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978896,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495100016,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__arm64_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495100016,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289003680,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__se_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289003680,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323904,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323904,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583261008,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261008,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307680,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307680,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```

```json
{
  "name": "compat_keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402672,
      "name": "compat_keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/compat_dh.c:16",
      "file": "security/keys/compat_dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat.c:__x32_compat_sys_keyctl",
        "security/keys/compat.c:__ia32_compat_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402672,
      "name": "compat_keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct compat_keyctl_kdf_params * kdf)
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
