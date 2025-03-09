# Function: <code>fscrypt_destroy_hkdf</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300976,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300976,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585984,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:174",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585984,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656736,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:174",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656736,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685808,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:174",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685808,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011504,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:179",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011504,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482064,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:179",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/crypto/keyring.c:fscrypt_key_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482064,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076816,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:179",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076816,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584303472,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:179",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303472,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520496,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:179",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:fscrypt_destroy_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520496,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493876496,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493876496,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227358776,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227358776,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287510384,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287510384,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273440208,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:wipe_master_key_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273440208,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269712,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269712,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582207472,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207472,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260192,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260192,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
```

```json
{
  "name": "fscrypt_destroy_hkdf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338784,
      "name": "fscrypt_destroy_hkdf",
      "external": true,
      "loc": "fs/crypto/hkdf.c:178",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/keyring.c:free_master_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338784,
      "name": "fscrypt_destroy_hkdf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void fscrypt_destroy_hkdf(struct fscrypt_hkdf * hkdf)
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
