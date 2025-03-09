# Function: <code>fat_free_clusters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581964784,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:550",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581964784,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 857
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176800,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:550",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176800,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266208,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:550",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266208,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350864,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:550",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350864,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582501584,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:550",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501584,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:550",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695914,
      "name": "fat_free_clusters.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582692656,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:549",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799026,
      "name": "fat_free_clusters.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582794592,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:549",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973903,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582968912,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080122,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583075520,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398591,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583394112,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591352429,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583509760,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295341,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583532832,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 899
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:553",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592279064,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071583890192,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:554",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594061401,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071584466368,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 978
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:554",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596089327,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071585129904,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:554",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596612690,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071585359232,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:554",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597518644,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071585593968,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494781536,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494781536,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228201316,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228201316,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288614576,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288614576,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274113878,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274113878,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048858,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583044256,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986010,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071582981408,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037466,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583032864,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
int fat_free_clusters(struct inode * inode, int cluster)
```

```json
{
  "name": "fat_free_clusters",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_free_clusters",
      "external": true,
      "loc": "fs/fat/fatent.c:552",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_alloc_clusters",
        "fs/fat/file.c:fat_truncate_blocks",
        "fs/fat/inode.c:fat_add_cluster",
        "fs/fat/namei_vfat.c:vfat_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126597,
      "name": "fat_free_clusters.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583121984,
      "name": "fat_free_clusters",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
