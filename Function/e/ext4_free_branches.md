# Function: <code>ext4_free_branches</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830256,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:1093",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830256,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026256,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:981",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026256,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582116384,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:981",
      "file": "fs/ext4/indirect.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116384,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955584,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:982",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955584,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582104640,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104640,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582292800,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:989",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292800,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391552,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:989",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391552,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560528,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560528,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661472,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661472,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582973344,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:987",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973344,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048960,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:988",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048960,
      "name": "ext4_free_branches",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074560,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:988",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074560,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583413104,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:992",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413104,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928624,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:992",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928624,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554864,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:999",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554864,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783616,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:1007",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783616,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585016480,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:1007",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016480,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494313944,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494313944,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227749700,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227749700,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288034160,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288034160,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273753610,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273753610,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630208,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630208,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567376,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567376,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620064,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620064,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
void ext4_free_branches(handle_t * handle, struct inode * inode, struct buffer_head * parent_bh, __le32 * first, __le32 * last, int depth)
```

```json
{
  "name": "ext4_free_branches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582702224,
      "name": "ext4_free_branches",
      "external": false,
      "loc": "fs/ext4/indirect.c:983",
      "file": "fs/ext4/indirect.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_remove_space",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_ind_truncate",
        "fs/ext4/indirect.c:ext4_free_branches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702224,
      "name": "ext4_free_branches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
