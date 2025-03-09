# Function: <code>trusted_tpm_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582214613,
      "name": "trusted_tpm_send",
      "external": false,
      "loc": "security/keys/trusted.c:358",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:oiap",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582438341,
      "name": "trusted_tpm_send",
      "external": false,
      "loc": "security/keys/trusted.c:358",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530533,
      "name": "trusted_tpm_send",
      "external": false,
      "loc": "security/keys/trusted.c:358",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582614180,
      "name": "trusted_tpm_send",
      "external": false,
      "loc": "security/keys/trusted.c:358",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582767796,
      "name": "trusted_tpm_send",
      "external": false,
      "loc": "security/keys/trusted.c:358",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582968683,
      "name": "trusted_tpm_send",
      "external": false,
      "loc": "security/keys/trusted.c:358",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:oiap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583079178,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:360",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:key_seal",
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:oiap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075200,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583263025,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258336,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583368913,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364224,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583703645,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:364",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698320,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583824921,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:364",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819584,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583850105,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:357",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844864,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584213145,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:357",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207840,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584816760,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:357",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584810832,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585516000,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:357",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509712,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747712,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:357",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741376,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585995056,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:357",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal",
        "security/keys/trusted-keys/trusted_tpm1.c:tpm_seal",
        "security/keys/trusted-keys/trusted_tpm1.c:oiap",
        "security/keys/trusted-keys/trusted_tpm1.c:osap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585988672,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495118504,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495112856,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228506112,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228501728,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289023132,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289016272,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274371868,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274367752,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583337649,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583332960,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583274753,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270064,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583321425,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316736,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
```

```json
{
  "name": "trusted_tpm_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416449,
      "name": "trusted_tpm_send",
      "external": true,
      "loc": "security/keys/trusted.c:364",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/trusted.c:tpm_unseal",
        "security/keys/trusted.c:tpm_seal",
        "security/keys/trusted.c:tpm_seal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411760,
      "name": "trusted_tpm_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int trusted_tpm_send(unsigned char * cmd, size_t buflen)
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
