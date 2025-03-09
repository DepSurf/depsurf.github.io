# Function: <code>bmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581100320,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1520",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100320,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265888,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1529",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265888,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343728,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1558",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343728,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399200,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1558",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399200,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581540800,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1558",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540800,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696192,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1548",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696192,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782544,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1589",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782544,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900432,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1602",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900432,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972768,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972768,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205760,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1698",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:ioctl_fibmap",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_next_log_block",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205760,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253200,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1699",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:ioctl_fibmap",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253200,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279088,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1706",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279088,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597072,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1710",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597072,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583128464,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1791",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128464,
      "name": "bmap",
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583698848,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1793",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698848,
      "name": "bmap",
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916720,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1837",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_bmap",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916720,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int bmap(struct inode * inode, sector_t * block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122496,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1785",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_bmap",
        "fs/ecryptfs/mmap.c:ecryptfs_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122496,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493479648,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493479648,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227042240,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227042240,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287038032,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287038032,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273156422,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273156422,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941504,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941504,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879088,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879088,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932816,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932816,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
sector_t bmap(struct inode * inode, sector_t block)
```

```json
{
  "name": "bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003936,
      "name": "bmap",
      "external": true,
      "loc": "fs/inode.c:1613",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:generic_swapfile_activate",
        "mm/page_io.c:generic_swapfile_activate",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "drivers/md/md-bitmap.c:read_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003936,
      "name": "bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>sector_t block</code> ➡️ <code>sector_t * block</code>
</li>
<li>
<b>Return type changed. </b>
<code>sector_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
