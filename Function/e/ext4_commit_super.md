# Function: <code>ext4_commit_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695824,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4315",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_error",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695824,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887568,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4477",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887568,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976576,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4602",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976576,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192720,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4710",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192720,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341392,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4720",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341392,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530784,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4831",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530784,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631872,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4894",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631872,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804512,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:4984",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804512,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907872,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907872,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221408,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5199",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221408,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323344,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5559",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:flush_stashed_error_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323344,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346160,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5605",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:flush_stashed_error_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346160,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583689984,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5460",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:flush_stashed_error_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689984,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240784,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5906",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:flush_stashed_error_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240784,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584885488,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:6058",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:flush_stashed_error_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885488,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585112656,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:6145",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:flush_stashed_error_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112656,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int ext4_commit_super(struct super_block * sb)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585345104,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:6173",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_freeze",
        "fs/ext4/super.c:ext4_freeze",
        "fs/ext4/super.c:ext4_freeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:update_super_work",
        "fs/ext4/super.c:ext4_handle_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345104,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494583344,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494583344,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228025964,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228025964,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288381184,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288381184,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273962868,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273962868,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582876608,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876608,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582813760,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582813760,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582865488,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582865488,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_commit_super(struct super_block * sb, int sync)
```

```json
{
  "name": "ext4_commit_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952144,
      "name": "ext4_commit_super",
      "external": false,
      "loc": "fs/ext4/super.c:5015",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_unfreeze",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_setup_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:__ext4_std_error",
        "fs/ext4/super.c:__ext4_error_file",
        "fs/ext4/super.c:__ext4_error_inode",
        "fs/ext4/super.c:__ext4_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952144,
      "name": "ext4_commit_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sync</code>
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
