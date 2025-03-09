# Function: <code>fuse_lock_owner_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086928,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:314",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086928,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302256,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:314",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302256,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582390592,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:315",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390592,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475040,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:310",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475040,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625984,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:310",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625984,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582818304,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:310",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_send_read",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582818304,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922320,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:314",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922320,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101952,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:320",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101952,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207424,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207424,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535200,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:341",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535200,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583645072,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:364",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_write",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645072,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583665440,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:368",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665440,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024496,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:371",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024496,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584612320,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:377",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612320,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585291584,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:377",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585291584,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521968,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:378",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521968,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585758832,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:379",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758832,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494927912,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494927912,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228337844,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_lk_fill",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228337844,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288798016,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288798016,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274235106,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274235106,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176160,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176160,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113312,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113312,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160192,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160192,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 fuse_lock_owner_id(struct fuse_conn * fc, fl_owner_t id)
```

```json
{
  "name": "fuse_lock_owner_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253728,
      "name": "fuse_lock_owner_id",
      "external": true,
      "loc": "fs/fuse/file.c:340",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_flush",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253728,
      "name": "fuse_lock_owner_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
