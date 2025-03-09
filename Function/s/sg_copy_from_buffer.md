# Function: <code>sg_copy_from_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016432,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:699",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill",
        "drivers/ata/libata-scsi.c:atapi_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016432,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307376,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:699",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307376,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426704,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:699",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426704,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447680,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:695",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447680,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583627808,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:736",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627808,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844096,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:851",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844096,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927792,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:851",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927792,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107680,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107680,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230880,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230880,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584636992,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_format_dsm_trim_descr",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636992,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756000,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:967",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_format_dsm_trim_descr",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756000,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584785632,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:967",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785632,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585216064,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:997",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585216064,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586053776,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:994",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053776,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037792,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:1004",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037792,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587292864,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:1006",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292864,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587578688,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:1008",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_simulate",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587578688,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496105904,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496105904,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229430764,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill",
        "drivers/mmc/host/sdhci.c:sdhci_request_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229430764,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290353120,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290353120,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275172128,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275172128,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199616,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199616,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134832,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134832,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183376,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183376,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
size_t sg_copy_from_buffer(struct scatterlist * sgl, unsigned int nents, const void * buf, size_t buflen)
```

```json
{
  "name": "sg_copy_from_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287728,
      "name": "sg_copy_from_buffer",
      "external": true,
      "loc": "lib/scatterlist.c:886",
      "file": "lib/scatterlist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat",
        "drivers/ata/libata-scsi.c:atapi_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287728,
      "name": "sg_copy_from_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
