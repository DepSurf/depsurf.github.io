# Function: <code>keyctl_dh_compute</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, void * reserved)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430592,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:80",
      "file": "security/keys/dh.c",
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
      "addr": 18446744071582430592,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, void * reserved)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522768,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:80",
      "file": "security/keys/dh.c",
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
      "addr": 18446744071582522768,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606768,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:422",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606768,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760256,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:422",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:SyS_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760256,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960288,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:415",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960288,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069824,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:415",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069824,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583254592,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254592,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360448,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360448,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696368,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696368,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817728,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817728,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841904,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841904,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204864,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204864,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807376,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:320",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807376,
      "name": "keyctl_dh_compute",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505760,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:320",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505760,
      "name": "keyctl_dh_compute",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585737392,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:300",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737392,
      "name": "keyctl_dh_compute",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984640,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:300",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__do_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984640,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495106808,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__arm64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495106808,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228497332,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228497332,
      "name": "keyctl_dh_compute",
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289010704,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289010704,
      "name": "keyctl_dh_compute",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274364292,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__se_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274364292,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329184,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329184,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266288,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266288,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312960,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312960,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdf)
```

```json
{
  "name": "keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407984,
      "name": "keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:410",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407984,
      "name": "keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, void * reserved)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct keyctl_kdf_params * kdf</code>
</li>
<li>
<b>Param removed. </b>
<code>void * reserved</code>
</li>
</ul>
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
