# Function: <code>setup_per_mode_key</code>

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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308256,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071582310481,
      "name": "setup_per_mode_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493885984,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493885984,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227366680,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227366680,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287521184,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287521184,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273447196,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273447196,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276992,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071582279217,
      "name": "setup_per_mode_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214752,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071582216977,
      "name": "setup_per_mode_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267472,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071582269697,
      "name": "setup_per_mode_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```

```json
{
  "name": "setup_per_mode_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_per_mode_key",
      "external": false,
      "loc": "fs/crypto/keysetup.c:208",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582346032,
      "name": "setup_per_mode_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071582348255,
      "name": "setup_per_mode_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int setup_per_mode_key(struct fscrypt_info * ci, struct fscrypt_master_key * mk)
```
</details>
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
