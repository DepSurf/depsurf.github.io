# Function: <code>journal_init_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
journal_t * journal_init_common()
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581922512,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1069",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/jbd2/journal.c:jbd2_journal_init_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922512,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
journal_t * journal_init_common()
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112320,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1093",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112320,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202304,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1093",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202304,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582287792,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1116",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287792,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436864,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1132",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436864,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1129",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626752,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071582638737,
      "name": "journal_init_common.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1129",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582728576,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071582740481,
      "name": "journal_init_common.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1112",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902160,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071582914333,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008848,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071583020931,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1124",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324320,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071583338214,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1303",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447520,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071591350601,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1303",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465440,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    },
    {
      "addr": 18446744071591293240,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1337",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819232,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071592274723,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1343",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388080,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
    },
    {
      "addr": 18446744071594056382,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585043552,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1346",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043552,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585272432,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1348",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272432,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585508720,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1519",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508720,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494693744,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494693744,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228136056,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228136056,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288518576,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288518576,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274052392,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274052392,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977584,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071582989667,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914736,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071582926819,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966192,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071582978275,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
journal_t * journal_init_common(struct block_device * bdev, struct block_device * fs_dev, long long unsigned int start, int len, int blocksize)
```

```json
{
  "name": "journal_init_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "journal_init_common",
      "external": false,
      "loc": "fs/jbd2/journal.c:1111",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583055360,
      "name": "journal_init_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    },
    {
      "addr": 18446744071583067358,
      "name": "journal_init_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param added. </b>
<code>struct block_device * fs_dev</code>
</li>
<li>
<b>Param added. </b>
<code>long long unsigned int start</code>
</li>
<li>
<b>Param added. </b>
<code>int len</code>
</li>
<li>
<b>Param added. </b>
<code>int blocksize</code>
</li>
</ul>
</details>
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
