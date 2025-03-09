# Function: <code>scatterwalk_map_and_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641056,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:107",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641056,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582890336,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:60",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890336,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582986912,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:60",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986912,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583036864,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:60",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036864,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583202176,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:60",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202176,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583410656,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:60",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410656,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583532368,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:60",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532368,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583720304,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720304,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583830016,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830016,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584225456,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225456,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584343840,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584343840,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584378320,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378320,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584773552,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773552,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585458288,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585458288,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586217184,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217184,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586452480,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586452480,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718368,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_final",
        "crypto/xts.c:xts_cts_done",
        "crypto/xts.c:xts_cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718368,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495641008,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495641008,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228996788,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228996788,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289772304,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289772304,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274795828,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274795828,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583798752,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798752,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583735808,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735808,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583782512,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782512,
      "name": "scatterwalk_map_and_copy",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void scatterwalk_map_and_copy(void * buf, struct scatterlist * sg, unsigned int start, unsigned int nbytes, int out)
```

```json
{
  "name": "scatterwalk_map_and_copy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583883536,
      "name": "scatterwalk_map_and_copy",
      "external": true,
      "loc": "crypto/scatterwalk.c:55",
      "file": "crypto/scatterwalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "crypto/seqiv.c:seqiv_aead_decrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/scompress.c:scomp_acomp_comp_decomp",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_final",
        "crypto/xts.c:cts_done",
        "crypto/xts.c:cts_done",
        "crypto/gcm.c:crypto_rfc4106_crypt",
        "crypto/gcm.c:crypto_gcm_verify",
        "crypto/gcm.c:gcm_enc_copy_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883536,
      "name": "scatterwalk_map_and_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
