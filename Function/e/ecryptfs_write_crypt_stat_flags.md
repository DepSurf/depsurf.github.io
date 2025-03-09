# Function: <code>ecryptfs_write_crypt_stat_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582016272,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:940",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016272,
      "name": "ecryptfs_write_crypt_stat_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582230844,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:933",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230016,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582320345,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:933",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319520,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582405080,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:933",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582404272,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555816,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:918",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555008,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582747912,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:918",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747104,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582851704,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:918",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850896,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583026397,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:901",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025648,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132605,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131856,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448697,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:888",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452784,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583561273,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:888",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565392,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583589018,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:883",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588000,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583947306,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:883",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946208,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584529149,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:883",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527920,
      "name": "ecryptfs_write_crypt_stat_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585200941,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:883",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199600,
      "name": "ecryptfs_write_crypt_stat_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585429949,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:859",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585428608,
      "name": "ecryptfs_write_crypt_stat_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585664621,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:859",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663280,
      "name": "ecryptfs_write_crypt_stat_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494841808,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494841808,
      "name": "ecryptfs_write_crypt_stat_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228261152,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228260404,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288692948,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288690992,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274164714,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274163920,
      "name": "ecryptfs_write_crypt_stat_flags",
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
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583101341,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100592,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583038493,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037744,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583089949,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583089200,
      "name": "ecryptfs_write_crypt_stat_flags",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ecryptfs_write_crypt_stat_flags(char * page_virt, struct ecryptfs_crypt_stat * crypt_stat, size_t * written)
```

```json
{
  "name": "ecryptfs_write_crypt_stat_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583179165,
      "name": "ecryptfs_write_crypt_stat_flags",
      "external": true,
      "loc": "fs/ecryptfs/crypto.c:903",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583178416,
      "name": "ecryptfs_write_crypt_stat_flags",
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
