# Function: <code>fscrypt_prepare_inline_crypt_key</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:126",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_setup_v2_file_key",
        "fs/crypto/keysetup.c:setup_per_mode_enc_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591342742,
      "name": "fscrypt_prepare_inline_crypt_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071582676720,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:126",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591285487,
      "name": "fscrypt_prepare_inline_crypt_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071582705456,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:126",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592242108,
      "name": "fscrypt_prepare_inline_crypt_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071583032016,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:158",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594021119,
      "name": "fscrypt_prepare_inline_crypt_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071583505920,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102848,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:153",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102848,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330352,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:153",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330352,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_inode_info * ci)
```

```json
{
  "name": "fscrypt_prepare_inline_crypt_key",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_prepare_inline_crypt_key",
      "external": true,
      "loc": "fs/crypto/inline_crypt.c:152",
      "file": "fs/crypto/inline_crypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487246,
      "name": "fscrypt_prepare_inline_crypt_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071584548096,
      "name": "fscrypt_prepare_inline_crypt_key",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int fscrypt_prepare_inline_crypt_key(struct fscrypt_prepared_key * prep_key, const u8 * raw_key, const struct fscrypt_info * ci)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct fscrypt_info * ci</code> ➡️ <code>const struct fscrypt_inode_info * ci</code>
</li>
</ul>
</details>
</li>
</ul>
