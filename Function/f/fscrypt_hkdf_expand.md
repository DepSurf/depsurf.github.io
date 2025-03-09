# Function: <code>fscrypt_hkdf_expand</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301043,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582300208,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:111",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586039,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582585216,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:111",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_iv_ino_lblk_32_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341574,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582655968,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:111",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284307,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582685024,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:116",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592240142,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583010720,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583481184,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:116",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583481184,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075920,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:116",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075920,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302576,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:116",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302576,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
int fscrypt_hkdf_expand(const struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584519600,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:116",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519600,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493875912,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493875912,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227358160,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227358160,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287509568,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287509568,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273439724,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273439724,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269779,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582268944,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207539,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582206704,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260259,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582259424,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```

```json
{
  "name": "fscrypt_hkdf_expand",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_hkdf_expand",
      "external": true,
      "loc": "fs/crypto/hkdf.c:115",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338851,
      "name": "fscrypt_hkdf_expand.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582338016,
      "name": "fscrypt_hkdf_expand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int fscrypt_hkdf_expand(struct fscrypt_hkdf * hkdf, u8 context, const u8 * info, unsigned int infolen, u8 * okm, unsigned int okmlen)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_hkdf * hkdf</code> ➡️ <code>const struct fscrypt_hkdf * hkdf</code>
</li>
</ul>
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
