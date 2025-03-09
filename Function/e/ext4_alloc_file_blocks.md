# Function: <code>ext4_alloc_file_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581741888,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4664",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741888,
      "name": "ext4_alloc_file_blocks.isra.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936944,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4668",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936944,
      "name": "ext4_alloc_file_blocks.isra.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582027008,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4658",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027008,
      "name": "ext4_alloc_file_blocks.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889664,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4653",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889664,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039776,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4653",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039776,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228112,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4647",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228112,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323200,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4546",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323200,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582490336,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4556",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582490336,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589872,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589872,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582899936,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4382",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899936,
      "name": "ext4_alloc_file_blocks.isra.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582971856,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4379",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971856,
      "name": "ext4_alloc_file_blocks.isra.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582997728,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4385",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997728,
      "name": "ext4_alloc_file_blocks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4424",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335776,
      "name": "ext4_alloc_file_blocks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
    },
    {
      "addr": 18446744071592251295,
      "name": "ext4_alloc_file_blocks.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4420",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844944,
      "name": "ext4_alloc_file_blocks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071594032322,
      "name": "ext4_alloc_file_blocks.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4424",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469072,
      "name": "ext4_alloc_file_blocks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    },
    {
      "addr": 18446744071596065607,
      "name": "ext4_alloc_file_blocks.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4416",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584697968,
      "name": "ext4_alloc_file_blocks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
    },
    {
      "addr": 18446744071596589504,
      "name": "ext4_alloc_file_blocks.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4448",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930592,
      "name": "ext4_alloc_file_blocks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
    },
    {
      "addr": 18446744071597495288,
      "name": "ext4_alloc_file_blocks.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494238672,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494238672,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227670360,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227670360,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287941792,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287941792,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273691918,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273691918,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558608,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558608,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582495776,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582495776,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548720,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548720,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```

```json
{
  "name": "ext4_alloc_file_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629872,
      "name": "ext4_alloc_file_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:4602",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/extents.c:ext4_zero_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629872,
      "name": "ext4_alloc_file_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ext4_alloc_file_blocks(struct file * file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags)
```
</details>
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
