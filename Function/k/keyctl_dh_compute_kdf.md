# Function: <code>keyctl_dh_compute_kdf</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605902,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:213",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582759362,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:213",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582959386,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:204",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583068942,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:204",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583253616,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583359435,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694720,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694720,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816080,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816080,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840256,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840256,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203216,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203216,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int keyctl_dh_compute_kdf(struct crypto_shash * hash, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805328,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:110",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805328,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int keyctl_dh_compute_kdf(struct crypto_shash * hash, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585503696,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:110",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503696,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int keyctl_dh_compute_kdf(struct crypto_shash * hash, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585735216,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:94",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735216,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int keyctl_dh_compute_kdf(struct crypto_shash * hash, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982464,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:94",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982464,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495104792,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495104792,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228495020,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228495020,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289009652,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274362558,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274362558,
      "name": "keyctl_dh_compute_kdf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583328171,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583265275,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583311947,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "keyctl_dh_compute_kdf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583406971,
      "name": "keyctl_dh_compute_kdf",
      "external": false,
      "loc": "security/keys/dh.c:199",
      "file": "security/keys/dh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_shash * hash</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kdf_sdesc * sdesc</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t lzero</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int keyctl_dh_compute_kdf(struct kdf_sdesc * sdesc, char * buffer, size_t buflen, uint8_t * kbuf, size_t kbuflen, size_t lzero)
```
</details>
</li>
</ul>
