# Function: <code>ext4_fname_free_filename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887168,
      "name": "ext4_fname_free_filename",
      "external": true,
      "loc": "fs/ext4/crypto_fname.c:464",
      "file": "fs/ext4/crypto_fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887168,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581806043,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2320",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796304,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895467,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2300",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885808,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582100127,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2336",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582249439,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2296",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582437664,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2297",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582537120,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2310",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582709111,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2367",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582811343,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583122292,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2523",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583201660,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2655",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583229424,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2707",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583573289,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2777",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336912,
      "name": "ext4_fname_free_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:58",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336912,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986048,
      "name": "ext4_fname_free_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:58",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986048,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585214064,
      "name": "ext4_fname_free_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:58",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214064,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_fname_free_filename(struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585446937,
      "name": "ext4_fname_free_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:62",
      "file": "fs/ext4/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent",
        "fs/ext4/namei.c:ext4_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447024,
      "name": "ext4_fname_free_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494481024,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227916968,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288241844,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273884016,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582780079,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582717247,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582768985,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
  "name": "ext4_fname_free_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582855231,
      "name": "ext4_fname_free_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2425",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void ext4_fname_free_filename(struct ext4_filename * fname)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void ext4_fname_free_filename(struct ext4_filename * fname)
```
</details>
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
