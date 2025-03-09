# Function: <code>ext4fs_dirhash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581722864,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:138",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722864,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917744,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:138",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917744,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582007808,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:138",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582007808,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939808,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:207",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939808,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1267
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
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088720,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:203",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088720,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276992,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:199",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276992,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1277
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
int ext4fs_dirhash(const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375632,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:199",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375632,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1313
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545264,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545264,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582646208,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582646208,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957152,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957152,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031328,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031328,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583057136,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:290",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583057136,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583394976,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:290",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394976,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909680,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:290",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909680,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535536,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:290",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535536,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764640,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:294",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764640,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997664,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:294",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997664,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494298328,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494298328,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227732396,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227732396,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288014624,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288014624,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273740556,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273740556,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614944,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614944,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552112,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552112,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603696,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603696,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1355
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
int ext4fs_dirhash(const struct inode * dir, const char * name, int len, struct dx_hash_info * hinfo)
```

```json
{
  "name": "ext4fs_dirhash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687312,
      "name": "ext4fs_dirhash",
      "external": true,
      "loc": "fs/ext4/hash.c:274",
      "file": "fs/ext4/hash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687312,
      "name": "ext4fs_dirhash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode * dir</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, len, hinfo</code> ➡️ <code>dir, name, len, hinfo</code>
</li>
</ul>
</details>
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
