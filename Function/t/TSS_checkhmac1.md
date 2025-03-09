# Function: <code>TSS_checkhmac1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582216736,
      "name": "TSS_checkhmac1",
      "external": false,
      "loc": "security/keys/trusted.c:175",
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
      "addr": 18446744071582216736,
      "name": "TSS_checkhmac1.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582435360,
      "name": "TSS_checkhmac1",
      "external": false,
      "loc": "security/keys/trusted.c:175",
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
      "addr": 18446744071582435360,
      "name": "TSS_checkhmac1.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582527552,
      "name": "TSS_checkhmac1",
      "external": false,
      "loc": "security/keys/trusted.c:175",
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
      "addr": 18446744071582527552,
      "name": "TSS_checkhmac1.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582611200,
      "name": "TSS_checkhmac1",
      "external": false,
      "loc": "security/keys/trusted.c:175",
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
      "addr": 18446744071582611200,
      "name": "TSS_checkhmac1.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582764784,
      "name": "TSS_checkhmac1",
      "external": false,
      "loc": "security/keys/trusted.c:175",
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
      "addr": 18446744071582764784,
      "name": "TSS_checkhmac1.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
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
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": false,
      "loc": "security/keys/trusted.c:175",
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
      "addr": 18446744071582964848,
      "name": "TSS_checkhmac1.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    },
    {
      "addr": 18446744071582970298,
      "name": "TSS_checkhmac1.constprop.6.cold.14",
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:176",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081462,
      "name": "TSS_checkhmac1.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071583074560,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266403,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583260896,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372305,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583366784,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:177",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707228,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583701328,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:177",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591361708,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583822608,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:170",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304577,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583847792,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:170",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592292338,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584210832,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:170",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594074508,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584814176,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513312,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:170",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513312,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585745024,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:170",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745024,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585992368,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:170",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585992368,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495114360,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495114360,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228504216,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228504216,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289020672,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289020672,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274368738,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274368738,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341041,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583335520,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278145,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583272624,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324817,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583319296,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
```

```json
{
  "name": "TSS_checkhmac1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "TSS_checkhmac1",
      "external": true,
      "loc": "security/keys/trusted.c:177",
      "file": "security/keys/trusted.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419841,
      "name": "TSS_checkhmac1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583414320,
      "name": "TSS_checkhmac1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int TSS_checkhmac1(unsigned char * buffer, const uint32_t command, const unsigned char * ononce, const unsigned char * key, unsigned int keylen, void (anon))
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
