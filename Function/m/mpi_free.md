# Function: <code>mpi_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143232,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig_asymmetric.c:asymmetric_verify",
        "crypto/asymmetric_keys/public_key.c:public_key_destroy",
        "crypto/asymmetric_keys/rsa.c:RSA_verify_signature",
        "crypto/asymmetric_keys/rsa.c:RSA_verify_signature",
        "crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate",
        "crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_free_signed_info",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143232,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437472,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437472,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563200,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "security/keys/dh.c:keyctl_dh_compute",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563200,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600752,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_exit_tfm",
        "crypto/dh.c:dh_exit_tfm",
        "crypto/dh.c:dh_exit_tfm",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600752,
      "name": "mpi_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846832,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846832,
      "name": "mpi_free",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584047665,
      "name": "mpi_free.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584047248,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_verify",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_sign",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify",
        "lib/digsig.c:digsig_verify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130609,
      "name": "mpi_free.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584130192,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319201,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584318784,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453889,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584453472,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_is_pubkey_valid",
        "crypto/dh.c:dh_is_pubkey_valid",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_set_priv_key",
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
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585017297,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585016880,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:175",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_is_pubkey_valid",
        "crypto/dh.c:dh_is_pubkey_valid",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_set_priv_key",
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
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/mpicoder.c:mpi_scanval",
        "lib/mpi/mpi-add.c:mpi_subm",
        "lib/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381150,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585164400,
      "name": "mpi_free",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:175",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_set_priv_key",
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
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/mpicoder.c:mpi_scanval",
        "lib/mpi/mpi-add.c:mpi_subm",
        "lib/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323542,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585044944,
      "name": "mpi_free",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:175",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_set_priv_key",
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
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/mpicoder.c:mpi_scanval",
        "lib/mpi/mpi-add.c:mpi_subm",
        "lib/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592338885,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071585488304,
      "name": "mpi_free",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:175",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_exit_tfm",
        "crypto/rsa.c:rsa_set_priv_key",
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
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_set_pub_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/mpicoder.c:mpi_scanval",
        "lib/mpi/mpi-add.c:mpi_subm",
        "lib/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594199344,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586632752,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875680,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:175",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/mpicoder.c:mpi_scanval",
        "lib/mpi/mpi-add.c:mpi_subm",
        "lib/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875680,
      "name": "mpi_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588147488,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:175",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_deinit",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/ec.c:mpi_ec_init",
        "lib/mpi/mpicoder.c:mpi_scanval",
        "lib/mpi/mpi-add.c:mpi_subm",
        "lib/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147488,
      "name": "mpi_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587716384,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/crypto/mpi/mpiutil.c:175",
      "file": "lib/crypto/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_deinit",
        "lib/crypto/mpi/ec.c:mpi_ec_init",
        "lib/crypto/mpi/ec.c:mpi_ec_init",
        "lib/crypto/mpi/ec.c:mpi_ec_init",
        "lib/crypto/mpi/mpicoder.c:mpi_scanval",
        "lib/crypto/mpi/mpi-add.c:mpi_subm",
        "lib/crypto/mpi/mpi-div.c:mpi_fdiv_qr",
        "lib/crypto/mpi/mpi-div.c:mpi_fdiv_q",
        "lib/crypto/mpi/mpi-div.c:mpi_fdiv_r",
        "lib/crypto/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/crypto/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/crypto/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/crypto/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/crypto/mpi/mpi-mod.c:mpi_barrett_free",
        "lib/crypto/mpi/mpiutil.c:mpi_snatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587716384,
      "name": "mpi_free",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496339464,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496339464,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229672688,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229672688,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290663264,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290663264,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275389512,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275389512,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422625,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584422208,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584357825,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584357408,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405537,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584405120,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void mpi_free(MPI a)
```

```json
{
  "name": "mpi_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_free",
      "external": true,
      "loc": "lib/mpi/mpiutil.c:109",
      "file": "lib/mpi/mpiutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_compute_value",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/dh.c:dh_clear_ctx",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_free_mpi_key",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_dec",
        "crypto/rsa.c:rsa_enc",
        "crypto/rsa.c:rsa_enc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511601,
      "name": "mpi_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584511184,
      "name": "mpi_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
