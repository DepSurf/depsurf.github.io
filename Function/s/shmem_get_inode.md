# Function: <code>shmem_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580578304,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:1424",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578304,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669808,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2080",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669808,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737120,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2117",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737120,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774048,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2154",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774048,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864176,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2165",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864176,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006768,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2184",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006768,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093760,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2146",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093760,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581147472,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2226",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147472,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205376,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205376,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405888,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2227",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405888,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434592,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2292",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434592,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454944,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2280",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454944,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709280,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2282",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709280,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080784,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2276",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080784,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
struct inode * shmem_get_inode(struct super_block * sb, struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556256,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2330",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556256,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
struct inode * shmem_get_inode(struct mnt_idmap * idmap, struct super_block * sb, struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2360",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582761536,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
    },
    {
      "addr": 18446744071596549407,
      "name": "shmem_get_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct inode * shmem_get_inode(struct mnt_idmap * idmap, struct super_block * sb, struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582936944,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2541",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936944,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492588496,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492588496,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226440508,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226440508,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285896384,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285896384,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272624784,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272624784,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174224,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174224,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121040,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121040,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165424,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165424,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
struct inode * shmem_get_inode(struct super_block * sb, const struct inode * dir, umode_t mode, dev_t dev, long unsigned int flags)
```

```json
{
  "name": "shmem_get_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581219488,
      "name": "shmem_get_inode",
      "external": false,
      "loc": "mm/shmem.c:2246",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_tmpfile",
        "mm/shmem.c:shmem_mknod"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219488,
      "name": "shmem_get_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode * dir</code> ➡️ <code>struct inode * dir</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap * idmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, dir, mode, dev, flags</code> ➡️ <code>idmap, sb, dir, mode, dev, flags</code>
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
