# Function: <code>ecryptfs_read_lower</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582010672,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:231",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010672,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582224102,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:231",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224016,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582313606,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:231",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313520,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582398308,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:233",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582398208,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582549166,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:233",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549024,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582741188,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:233",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741024,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582844948,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:233",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844784,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583020084,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019920,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583126276,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126112,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583446468,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446304,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583559172,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559008,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583582612,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582448,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583940628,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940464,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584521492,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521312,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585192388,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585192192,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585421428,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585421232,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585656125,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585655952,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494835964,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494835768,
      "name": "ecryptfs_read_lower",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228255124,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228254968,
      "name": "ecryptfs_read_lower",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288682908,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288682672,
      "name": "ecryptfs_read_lower",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274158946,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274158814,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583095012,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094848,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583032164,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032000,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583083620,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583083456,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int ecryptfs_read_lower(char * data, loff_t offset, size_t size, struct inode * ecryptfs_inode)
```

```json
{
  "name": "ecryptfs_read_lower",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583172867,
      "name": "ecryptfs_read_lower",
      "external": true,
      "loc": "fs/ecryptfs/read_write.c:219",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": [
        "fs/ecryptfs/crypto.c:ecryptfs_read_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583172736,
      "name": "ecryptfs_read_lower",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
