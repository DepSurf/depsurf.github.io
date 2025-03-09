# Function: <code>fscrypt_fname_encrypted_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 fscrypt_fname_encrypted_size(struct inode * inode, u32 ilen)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581503610,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:227",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_alloc_buffer"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503520,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
u32 fscrypt_fname_encrypted_size(const struct inode * inode, u32 ilen)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581589018,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:212",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_alloc_buffer"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588928,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u32 fscrypt_fname_encrypted_size(const struct inode * inode, u32 ilen)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581649087,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:214",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_alloc_buffer"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581649008,
      "name": "fscrypt_fname_encrypted_size",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 fscrypt_fname_encrypted_size(const struct inode * inode, u32 ilen)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581794511,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:191",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_fname_alloc_buffer"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794432,
      "name": "fscrypt_fname_encrypted_size",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581970430,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:184",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971024,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582057406,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:186",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058000,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218508,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:185",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218816,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582298880,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298880,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584016,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:262",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584016,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
bool fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582654864,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:236",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654864,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582683920,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:236",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename",
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683920,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583009695,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:260",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010352,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fscrypt_fname_encrypted_size(const union fscrypt_policy * policy, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583480125,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:267",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": [
        "fs/crypto/hooks.c:fscrypt_prepare_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480800,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584074781,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:299",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073232,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584301469,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:299",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299904,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584518445,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:299",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584516880,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493874456,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493874456,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227356776,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227356776,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287507584,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287507584,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273438608,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273438608,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582267616,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267616,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582205376,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205376,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582258096,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258096,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool fscrypt_fname_encrypted_size(const struct inode * inode, u32 orig_len, u32 max_len, u32 * encrypted_len_ret)
```

```json
{
  "name": "fscrypt_fname_encrypted_size",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582336688,
      "name": "fscrypt_fname_encrypted_size",
      "external": true,
      "loc": "fs/crypto/fname.c:181",
      "file": "fs/crypto/fname.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/fname.c:fscrypt_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582336688,
      "name": "fscrypt_fname_encrypted_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
u32 fscrypt_fname_encrypted_size(struct inode * inode, u32 ilen)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode * inode</code> ➡️ <code>const struct inode * inode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 orig_len</code>
</li>
<li>
<b>Param added. </b>
<code>u32 max_len</code>
</li>
<li>
<b>Param added. </b>
<code>u32 * encrypted_len_ret</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ilen</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const union fscrypt_policy * policy</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct inode * inode</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>const union fscrypt_policy * policy</code>
</li>
</ul>
</details>
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
