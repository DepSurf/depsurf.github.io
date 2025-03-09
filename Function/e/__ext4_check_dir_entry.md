# Function: <code>__ext4_check_dir_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535200,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:60",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:empty_inline_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535200,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720816,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:60",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720816,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581808432,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:60",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808432,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880592,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:60",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880592,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030656,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:61",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030656,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218944,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:62",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218944,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313792,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:62",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:htree_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313792,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481840,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481840,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581040,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581040,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582892261,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_check_all_de"
      ],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889696,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582964597,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_check_all_de"
      ],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961936,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987840,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:78",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987840,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323904,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:78",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323904,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831920,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:78",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831920,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455200,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:78",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455200,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684112,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:78",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684112,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916928,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:78",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:make_indexed_dir",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:do_split",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916928,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494229992,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494229992,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227659320,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227659320,
      "name": "__ext4_check_dir_entry",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287927472,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287927472,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273683528,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273683528,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549776,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549776,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486944,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486944,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539888,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539888,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __ext4_check_dir_entry(const char * function, unsigned int line, struct inode * dir, struct file * filp, struct ext4_dir_entry_2 * de, struct buffer_head * bh, char * buf, int size, unsigned int offset)
```

```json
{
  "name": "__ext4_check_dir_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621024,
      "name": "__ext4_check_dir_entry",
      "external": true,
      "loc": "fs/ext4/dir.c:66",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_check_all_de",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/inline.c:empty_inline_dir",
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_inlinedir_to_tree",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir",
        "fs/ext4/namei.c:htree_dirblock_to_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582621024,
      "name": "__ext4_check_dir_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
