# Function: <code>fname_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505472,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:123",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505472,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590656,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:108",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590656,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650704,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:108",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650704,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796064,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:89",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796064,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968976,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:90",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968976,
      "name": "fname_decrypt.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:91",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055888,
      "name": "fname_decrypt.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
    },
    {
      "addr": 18446744071582058076,
      "name": "fname_decrypt.isra.5.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:90",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216896,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582218892,
      "name": "fname_decrypt.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297728,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582299711,
      "name": "fname_decrypt.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:166",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582720,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071582584872,
      "name": "fname_decrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:140",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653504,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071591341470,
      "name": "fname_decrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:140",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682592,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071591284203,
      "name": "fname_decrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:144",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008112,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071592239853,
      "name": "fname_decrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:151",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478288,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071594018788,
      "name": "fname_decrypt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073360,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:153",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073360,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584300032,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:153",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300032,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584517008,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:153",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584517008,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493873168,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493873168,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227355508,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227355508,
      "name": "fname_decrypt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287505920,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287505920,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273437570,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273437570,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266464,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582268447,
      "name": "fname_decrypt.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204224,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582206207,
      "name": "fname_decrypt.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256944,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582258927,
      "name": "fname_decrypt.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fname_decrypt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fname_decrypt",
      "external": false,
      "loc": "fs/crypto/fname.c:88",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_fname_disk_to_usr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335536,
      "name": "fname_decrypt.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446744071582337519,
      "name": "fname_decrypt.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```
</details>
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fname_decrypt(const struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fname_decrypt(struct inode * inode, const struct fscrypt_str * iname, struct fscrypt_str * oname)
```
</details>
</li>
</ul>
