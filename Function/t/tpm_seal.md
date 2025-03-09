# Function: <code>tpm_seal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582219241,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:459",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582437993,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:459",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530185,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:459",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582613792,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:459",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582767408,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:459",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582967636,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:458",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583078787,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:462",
      "file": "security/keys/trusted.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446744071583263232,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071583266571,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446744071583369120,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071583372473,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:461",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704128,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1504
    },
    {
      "addr": 18446744071583707392,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:464",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:key_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825424,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1490
    },
    {
      "addr": 18446744071591361865,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:457",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850880,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1543
    },
    {
      "addr": 18446744071591304734,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:457",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213952,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1668
    },
    {
      "addr": 18446744071592292495,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:457",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584817632,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1706
    },
    {
      "addr": 18446744071594074676,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585516992,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:457",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516992,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748704,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:457",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748704,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1745
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996048,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted-keys/trusted_tpm1.c:457",
      "file": "security/keys/trusted-keys/trusted_tpm1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996048,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495118800,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446603336495118800,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1304
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228506392,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 3228506392,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289023536,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 13835058055289023536,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1740
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274372170,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446743936274372170,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1422
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446744071583337856,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071583341209,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446744071583274960,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071583278313,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446744071583321632,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071583324985,
      "name": "tpm_seal.cold",
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
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
```

```json
{
  "name": "tpm_seal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_seal",
      "external": false,
      "loc": "security/keys/trusted.c:467",
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
      "addr": 18446744071583416656,
      "name": "tpm_seal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071583420009,
      "name": "tpm_seal.cold",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int tpm_seal(struct tpm_buf * tb, uint16_t keytype, uint32_t keyhandle, const unsigned char * keyauth, const unsigned char * data, uint32_t datalen, unsigned char * blob, uint32_t * bloblen, const unsigned char * blobauth, const unsigned char * pcrinfo, uint32_t pcrinfosize)
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
