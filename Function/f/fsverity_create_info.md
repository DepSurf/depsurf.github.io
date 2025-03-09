# Function: <code>fsverity_create_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322541,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582321632,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:148",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:ensure_verity_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611929,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582610928,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:148",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:ensure_verity_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343682,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582683232,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:149",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591286422,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071582712016,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:149",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592243174,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071583038656,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, struct fsverity_descriptor * desc)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:149",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594022222,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071583513232,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, struct fsverity_descriptor * desc)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:149",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596059206,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584111248,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, struct fsverity_descriptor * desc)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:180",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:__fsverity_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596583107,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071584337248,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, struct fsverity_descriptor * desc)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:180",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:__fsverity_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597487473,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071584555456,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493902872,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493902872,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227381736,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227381736,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287539840,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287539840,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273459308,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273459308,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291277,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582290368,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229037,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582228128,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281757,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582280848,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```

```json
{
  "name": "fsverity_create_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_create_info",
      "external": true,
      "loc": "fs/verity/open.c:147",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360317,
      "name": "fsverity_create_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071582359408,
      "name": "fsverity_create_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct fsverity_info * fsverity_create_info(const struct inode * inode, void * _desc, size_t desc_size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsverity_descriptor * desc</code>
</li>
<li>
<b>Param removed. </b>
<code>void * _desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t desc_size</code>
</li>
</ul>
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
