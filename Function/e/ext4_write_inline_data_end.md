# Function: <code>ext4_write_inline_data_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863808,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:716",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863808,
      "name": "ext4_write_inline_data_end",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059904,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:717",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059904,
      "name": "ext4_write_inline_data_end",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149664,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:728",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149664,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969216,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:731",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969216,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118448,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:722",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118448,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307072,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:726",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307072,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405776,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405776,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574544,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574544,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675504,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675504,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987216,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987216,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583062880,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583062880,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583088272,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583088272,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427184,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:734",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427184,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1227
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945120,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:737",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945120,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1413
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571856,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:736",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571856,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1408
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct folio * folio)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584799440,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:743",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799440,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 950
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct folio * folio)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032336,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:742",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032336,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 950
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494328320,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494328320,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227763700,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227763700,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288052288,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288052288,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273764832,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273764832,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644240,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644240,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582581408,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581408,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634096,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634096,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ext4_write_inline_data_end(struct inode * inode, loff_t pos, unsigned int len, unsigned int copied, struct page * page)
```

```json
{
  "name": "ext4_write_inline_data_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717344,
      "name": "ext4_write_inline_data_end",
      "external": true,
      "loc": "fs/ext4/inline.c:729",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717344,
      "name": "ext4_write_inline_data_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
