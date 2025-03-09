# Function: <code>ext4_release_io_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595824,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:124",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_io_rsv_work",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_put_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595824,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581786480,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:123",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786480,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581876064,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:123",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876064,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112656,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:122",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112656,
      "name": "ext4_release_io_end",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261664,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:123",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261664,
      "name": "ext4_release_io_end",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449696,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:123",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449696,
      "name": "ext4_release_io_end",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549168,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:123",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549168,
      "name": "ext4_release_io_end",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721392,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071582724356,
      "name": "ext4_release_io_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582823872,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823872,
      "name": "ext4_release_io_end",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135456,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:151",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135456,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583216096,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:148",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216096,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243600,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:148",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243600,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585696,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:148",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585696,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123408,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:150",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123408,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584757040,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:150",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584757040,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584980928,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:150",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980928,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212064,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:150",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212064,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494494904,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494494904,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227931816,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227931816,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288259776,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288259776,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273894632,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273894632,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582792608,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792608,
      "name": "ext4_release_io_end",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582729760,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729760,
      "name": "ext4_release_io_end",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582781488,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781488,
      "name": "ext4_release_io_end",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_release_io_end(ext4_io_end_t * io_end)
```

```json
{
  "name": "ext4_release_io_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582867856,
      "name": "ext4_release_io_end",
      "external": false,
      "loc": "fs/ext4/page-io.c:115",
      "file": "fs/ext4/page-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867856,
      "name": "ext4_release_io_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
