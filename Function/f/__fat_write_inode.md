# Function: <code>__fat_write_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972704,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:742",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972704,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184592,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:825",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184592,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274032,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:825",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274032,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358624,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:825",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358624,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582509424,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:825",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582509424,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:844",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704240,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
    },
    {
      "addr": 18446744071582711192,
      "name": "__fat_write_inode.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:840",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811296,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071582815435,
      "name": "__fat_write_inode.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:835",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986320,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071582990446,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583092528,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071583096640,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411296,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071583415583,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:846",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526832,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071591353446,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:846",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549984,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
    },
    {
      "addr": 18446744071591296368,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908144,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071592280840,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:851",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482000,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071594062581,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:846",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146752,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    },
    {
      "addr": 18446744071596089961,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:846",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585375904,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    },
    {
      "addr": 18446744071596613260,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:851",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610640,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071597519214,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494795744,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494795744,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228211668,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228211668,
      "name": "__fat_write_inode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288627120,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288627120,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274125610,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274125610,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061264,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071583065376,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998416,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071583002528,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049872,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071583053984,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __fat_write_inode(struct inode * inode, int wait)
```

```json
{
  "name": "__fat_write_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__fat_write_inode",
      "external": false,
      "loc": "fs/fat/inode.c:847",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_sync_inode",
        "fs/fat/inode.c:fat_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131424,
      "name": "__fat_write_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
    },
    {
      "addr": 18446744071583142295,
      "name": "__fat_write_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
