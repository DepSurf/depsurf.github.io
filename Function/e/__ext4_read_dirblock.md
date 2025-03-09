# Function: <code>__ext4_read_dirblock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605248,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:89",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605248,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797600,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:89",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797600,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887072,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:89",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887072,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082528,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:89",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082528,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232144,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:90",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232144,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582422288,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:91",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582422288,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521776,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:91",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521776,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582690128,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690128,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792320,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792320,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583105760,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105760,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184816,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184816,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211216,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211216,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583555232,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:103",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583555232,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090784,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:119",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090784,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:124",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724432,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071596081072,
      "name": "__ext4_read_dirblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:124",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947792,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 861
    },
    {
      "addr": 18446744071596604243,
      "name": "__ext4_read_dirblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:124",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585179104,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071597509675,
      "name": "__ext4_read_dirblock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494462080,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494462080,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227897748,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:__ext4_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227897748,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288217664,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288217664,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273869280,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273869280,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582761056,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582761056,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698224,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698224,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751296,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751296,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
struct buffer_head * __ext4_read_dirblock(struct inode * inode, ext4_lblk_t block, dirblock_type_t type, const char * func, unsigned int line)
```

```json
{
  "name": "__ext4_read_dirblock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836192,
      "name": "__ext4_read_dirblock",
      "external": false,
      "loc": "fs/ext4/namei.c:102",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename_dir_prepare",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_empty_dir",
        "fs/ext4/namei.c:ext4_dx_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_dx_find_entry",
        "fs/ext4/namei.c:htree_dirblock_to_tree",
        "fs/ext4/namei.c:ext4_htree_next_block",
        "fs/ext4/namei.c:dx_probe",
        "fs/ext4/namei.c:dx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836192,
      "name": "__ext4_read_dirblock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
