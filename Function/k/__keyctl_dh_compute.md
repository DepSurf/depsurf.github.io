# Function: <code>__keyctl_dh_compute</code>

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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604448,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:239",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604448,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2306
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582757920,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:239",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582757920,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:232",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960415,
      "name": "__keyctl_dh_compute.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582958160,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2118
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:232",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069951,
      "name": "__keyctl_dh_compute.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583067728,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2091
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254730,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583252464,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2118
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360586,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583358272,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2174
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694960,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694960,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1399
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816320,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816320,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1399
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840496,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840496,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1393
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203456,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203456,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1393
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:138",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594074242,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584805600,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1769
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585503984,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:138",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503984,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1745
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585735504,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:122",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735504,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1860
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982752,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:122",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982752,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1860
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495105504,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495105504,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1300
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228495712,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228495712,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1620
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289008304,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289008304,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2400
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274363122,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274363122,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329322,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583327008,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2174
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266426,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583264112,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2174
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313098,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583310784,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2174
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
```

```json
{
  "name": "__keyctl_dh_compute",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__keyctl_dh_compute",
      "external": true,
      "loc": "security/keys/dh.c:227",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/compat_dh.c:compat_keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408122,
      "name": "__keyctl_dh_compute.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583405808,
      "name": "__keyctl_dh_compute",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2174
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
long int __keyctl_dh_compute(struct keyctl_dh_params * params, char * buffer, size_t buflen, struct keyctl_kdf_params * kdfcopy)
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
