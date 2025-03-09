# Function: <code>ext4_update_dx_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581604336,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2363",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ]
    },
    {
      "addr": 18446744071581860856,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2363",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604336,
      "name": "ext4_update_dx_flag.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581821874,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2391",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ]
    },
    {
      "addr": 18446744071582056639,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2391",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796640,
      "name": "ext4_update_dx_flag.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911148,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2371",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ]
    },
    {
      "addr": 18446744071582145694,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2371",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886144,
      "name": "ext4_update_dx_flag.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581965537,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2384",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582106819,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2384",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081888,
      "name": "ext4_update_dx_flag.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582114577,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2344",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582255794,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2344",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231504,
      "name": "ext4_update_dx_flag.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582303520,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2345",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582444205,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2345",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582402144,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2358",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582543677,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2358",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582568274,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2439",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582715597,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2439",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582669218,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582818038,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582980338,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2595",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583127646,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2595",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583056914,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2727",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583207181,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2727",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583082997,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2780",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234582,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2780",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583422031,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2850",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580262,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2850",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583938714,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2807",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117259,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2807",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_update_dx_flag(struct inode * inode)
```

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584563851,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2817",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584750798,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2817",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722256,
      "name": "ext4_update_dx_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_update_dx_flag(struct inode * inode)
```

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584792795,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2809",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584974419,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2809",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945616,
      "name": "ext4_update_dx_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ext4_update_dx_flag(struct inode * inode)
```

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585025648,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2826",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205391,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2826",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176944,
      "name": "ext4_update_dx_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494322052,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494488196,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227758252,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_add_dirent_to_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 3227925568,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288044908,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288251860,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273761472,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273889744,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582637954,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582786774,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582575122,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582723942,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582627810,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582775686,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_update_dx_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582710946,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582861926,
      "name": "ext4_update_dx_flag",
      "external": false,
      "loc": "fs/ext4/ext4.h:2497",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ext4_update_dx_flag(struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
