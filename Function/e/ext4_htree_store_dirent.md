# Function: <code>ext4_htree_store_dirent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct ext4_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538080,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:418",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538080,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723776,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:434",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723776,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811360,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:435",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811360,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883552,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:435",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883552,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033584,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:436",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033584,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221920,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:437",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221920,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316816,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:437",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316816,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483840,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:437",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483840,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583104,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583104,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582891840,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:443",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582891840,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964176,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:441",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964176,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990464,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:460",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990464,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583326656,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:460",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326656,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583834816,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:459",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583834816,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584458032,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:459",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458032,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:459",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596589222,
      "name": "ext4_htree_store_dirent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071584686800,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919616,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:459",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919616,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494232152,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494232152,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227662788,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227662788,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287931408,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287931408,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273685772,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273685772,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551840,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551840,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489008,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489008,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541952,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541952,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int ext4_htree_store_dirent(struct file * dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 * dirent, struct fscrypt_str * ent_name)
```

```json
{
  "name": "ext4_htree_store_dirent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582623072,
      "name": "ext4_htree_store_dirent",
      "external": true,
      "loc": "fs/ext4/dir.c:444",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:ext4_htree_fill_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582623072,
      "name": "ext4_htree_store_dirent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ext4_str * ent_name</code> ➡️ <code>struct fscrypt_str * ent_name</code>
</li>
</ul>
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
