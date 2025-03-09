# Function: <code>ext4_inode_is_fast_symlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566848,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:142",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/symlink.c:ext4_encrypted_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566848,
      "name": "ext4_inode_is_fast_symlink",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751600,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:148",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751600,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839712,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:148",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839712,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581998443,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:149",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": [
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989456,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582138880,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:150",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/symlink.c:ext4_encrypted_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138880,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582327856,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327856,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582426448,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426448,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582595664,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595664,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582696432,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696432,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583008544,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:149",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008544,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583084064,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:149",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583084064,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583109088,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:150",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109088,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448570,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:149",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592258183,
      "name": "ext4_inode_is_fast_symlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583448544,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:147",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594039432,
      "name": "ext4_inode_is_fast_symlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071583969984,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:147",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596072434,
      "name": "ext4_inode_is_fast_symlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584597888,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:146",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596595937,
      "name": "ext4_inode_is_fast_symlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071584824192,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:146",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597501456,
      "name": "ext4_inode_is_fast_symlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071585057168,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494353120,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494353120,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227786188,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227786188,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288081968,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288081968,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273783004,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273783004,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582665168,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665168,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582602336,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602336,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582655024,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655024,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int ext4_inode_is_fast_symlink(struct inode * inode)
```

```json
{
  "name": "ext4_inode_is_fast_symlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582738688,
      "name": "ext4_inode_is_fast_symlink",
      "external": true,
      "loc": "fs/ext4/inode.c:151",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738688,
      "name": "ext4_inode_is_fast_symlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
