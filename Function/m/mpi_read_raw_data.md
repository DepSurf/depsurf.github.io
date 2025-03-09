# Function: <code>mpi_read_raw_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132208,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:32",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/x509_cert_parser.c:rsa_extract_mpi",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_signature"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132208,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426368,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:mpi_from_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426368,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583552016,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:mpi_from_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583552016,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589616,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589616,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583835760,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583835760,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038330,
      "name": "mpi_read_raw_data.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584036272,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121102,
      "name": "mpi_read_raw_data.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584119008,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584309864,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584307920,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444536,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584442592,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007900,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585005952,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:36",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381049,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585142144,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:36",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323441,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585022736,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:36",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592337735,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585465664,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:36",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594198189,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071586608304,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587850144,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:36",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850144,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588121696,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:36",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121696,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690432,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/crypto/mpi/mpicoder.c:36",
      "file": "lib/crypto/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/crypto/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690432,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496328944,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496328944,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229662404,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229662404,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290648432,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290648432,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275381172,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275381172,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413272,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584411328,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348472,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584346528,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396184,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584394240,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
MPI mpi_read_raw_data(const void * xbuffer, size_t nbytes)
```

```json
{
  "name": "mpi_read_raw_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_read_raw_data",
      "external": true,
      "loc": "lib/mpi/mpicoder.c:35",
      "file": "lib/mpi/mpicoder.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/dh.c:dh_set_secret",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_priv_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "lib/mpi/mpicoder.c:mpi_read_from_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502248,
      "name": "mpi_read_raw_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584500304,
      "name": "mpi_read_raw_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
