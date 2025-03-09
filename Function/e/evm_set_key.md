# Function: <code>evm_set_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582876864,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876864,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582974320,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974320,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023904,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023904,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583188976,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583188976,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:55",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397766,
      "name": "evm_set_key.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583396976,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583517059,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:55",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517830,
      "name": "evm_set_key.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071583517024,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583705480,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705469,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583704704,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583815256,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815245,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583814480,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:50",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210643,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071584208656,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:50",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591370563,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071584327040,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:50",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591313255,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071584361536,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592309979,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071584756064,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594092478,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071585438112,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586195824,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195824,
      "name": "evm_set_key",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586433440,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586433440,
      "name": "evm_set_key",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699168,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699168,
      "name": "evm_set_key",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495620272,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495620272,
      "name": "evm_set_key",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228979656,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228979656,
      "name": "evm_set_key",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289741488,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289741488,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274779714,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274779714,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583783992,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583783981,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583783216,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721048,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721037,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583720272,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583767752,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767741,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583766976,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```

```json
{
  "name": "evm_set_key",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583868744,
      "name": "evm_set_key",
      "external": true,
      "loc": "security/integrity/evm/evm_crypto.c:52",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:evm_init_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868733,
      "name": "evm_set_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583867968,
      "name": "evm_set_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int evm_set_key(void * key, size_t keylen)
```
</details>
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
