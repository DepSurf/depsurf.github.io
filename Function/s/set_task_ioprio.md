# Function: <code>set_task_ioprio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582833552,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:32",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582833552,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113152,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:32",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113152,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224864,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:32",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224864,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583278848,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:35",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278848,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583459104,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:35",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set",
        "block/ioprio.c:SyS_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459104,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670384,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:35",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670384,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583777664,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:35",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777664,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583967392,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967392,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584070752,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070752,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463104,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463104,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578144,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578144,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584610208,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610208,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585024576,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024576,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585650512,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/blk-ioc.c:255",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_fill_super",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650512,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586423616,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/blk-ioc.c:255",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423616,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671168,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/blk-ioc.c:251",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671168,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942064,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/blk-ioc.c:251",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_load_and_init_journal",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942064,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495914096,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__arm64_sys_ioprio_set",
        "block/ioprio.c:__arm64_sys_ioprio_set",
        "block/ioprio.c:__arm64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495914096,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229256608,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__se_sys_ioprio_set",
        "block/ioprio.c:__se_sys_ioprio_set",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229256608,
      "name": "set_task_ioprio",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290124016,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__se_sys_ioprio_set",
        "block/ioprio.c:__se_sys_ioprio_set",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290124016,
      "name": "set_task_ioprio",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275027632,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__se_sys_ioprio_set",
        "block/ioprio.c:__se_sys_ioprio_set",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275027632,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584039488,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039488,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583975248,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975248,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584023248,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023248,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int set_task_ioprio(struct task_struct * task, int ioprio)
```

```json
{
  "name": "set_task_ioprio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125792,
      "name": "set_task_ioprio",
      "external": true,
      "loc": "block/ioprio.c:36",
      "file": "block/ioprio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125792,
      "name": "set_task_ioprio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
