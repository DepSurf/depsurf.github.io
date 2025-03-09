# Function: <code>fscrypt_init_hkdf</code>

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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301011,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582299984,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:63",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586007,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582584944,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:63",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341542,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582655696,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:63",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284275,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582684752,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:68",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592240110,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583010448,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:68",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594018914,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071583480896,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075584,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:68",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075584,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302240,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:68",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302240,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584519264,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:68",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:add_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519264,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493875608,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493875608,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227357856,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227357856,
      "name": "fscrypt_init_hkdf",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287509184,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287509184,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273439490,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273439490,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269747,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582268720,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207507,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582206480,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260227,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582259200,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```

```json
{
  "name": "fscrypt_init_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_init_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:67",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338819,
      "name": "fscrypt_init_hkdf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071582337792,
      "name": "fscrypt_init_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int fscrypt_init_hkdf(struct fscrypt_hkdf * hkdf, const u8 * master_key, unsigned int master_key_size)
```
</details>
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
