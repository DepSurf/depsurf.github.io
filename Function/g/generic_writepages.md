# Function: <code>generic_writepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521264,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2319",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521264,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580613664,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2364",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613664,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580680928,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2331",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580680928,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580717138,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2331",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714160,
      "name": "generic_writepages",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580802645,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2314",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799680,
      "name": "generic_writepages",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580939196,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2315",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935200,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581015164,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2309",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012144,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078193,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2316",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075264,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134145,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131248,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581318690,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2328",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310144,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581360722,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2326",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352384,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581379927,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2326",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375888,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581629210,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2335",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "block/fops.c:blkdev_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624864,
      "name": "generic_writepages",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991249,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2414",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:jbd2_journal_submit_inode_data_buffers",
        "block/fops.c:blkdev_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980448,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582427809,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2552",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_submit_inode_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416976,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492506916,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492503240,
      "name": "generic_writepages",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226378788,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226375664,
      "name": "generic_writepages",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285796148,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285791744,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272566742,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272563926,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581102993,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100096,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581050113,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047216,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094193,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091296,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
```

```json
{
  "name": "generic_writepages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156364,
      "name": "generic_writepages",
      "external": true,
      "loc": "mm/page-writeback.c:2318",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:do_writepages",
        "mm/page-writeback.c:do_writepages"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_writepages",
        "fs/mpage.c:mpage_writepages",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/jbd2/commit.c:journal_submit_data_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153456,
      "name": "generic_writepages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int generic_writepages(struct address_space * mapping, struct writeback_control * wbc)
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
