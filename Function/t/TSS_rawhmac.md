# Function: <code>TSS_rawhmac</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215904,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215904,
      "name": "TSS_rawhmac.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582434544,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434544,
      "name": "TSS_rawhmac.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582526736,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526736,
      "name": "TSS_rawhmac.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582610352,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610352,
      "name": "TSS_rawhmac.constprop.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582763920,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763920,
      "name": "TSS_rawhmac.constprop.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964000,
      "name": "TSS_rawhmac.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071582970246,
      "name": "TSS_rawhmac.constprop.8.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:77",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073696,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071583081410,
      "name": "TSS_rawhmac.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259984,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583266349,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365872,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583372251,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:75",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699616,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583707147,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:75",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820896,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071591361627,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846080,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071591304496,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209120,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071592292257,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812224,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071594074428,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511248,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511248,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742960,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742960,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585990304,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:68",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:osap",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585990304,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495113352,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495113352,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228503464,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228503464,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289019664,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289019664,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274368170,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274368170,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334608,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583340987,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271712,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583278091,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583318384,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583324763,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_rawhmac",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_rawhmac",
      "external": false,
      "loc": "security/keys/trusted.c:75",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:TSS_checkhmac1",
        "security/keys/trusted.c:TSS_authhmac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413408,
      "name": "TSS_rawhmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071583419787,
      "name": "TSS_rawhmac.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int TSS_rawhmac(unsigned char * digest, const unsigned char * key, unsigned int keylen, void (anon))
```
</details>
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
