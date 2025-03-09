# Function: <code>inode_init_once</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101600,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:355",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101600,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267264,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:362",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267264,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345136,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:364",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345136,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400512,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:365",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400512,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542128,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:365",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542128,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697424,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:371",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697424,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783776,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:371",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783776,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901952,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:384",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901952,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974192,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974192,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206736,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:389",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206736,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254208,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:390",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254208,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280112,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:390",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280112,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598160,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:394",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "block/bdev.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598160,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130160,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:418",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "block/bdev.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130160,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700368,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:416",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "block/bdev.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700368,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918240,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:416",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "block/bdev.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918240,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124048,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:417",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "fs/tracefs/inode.c:init_once",
        "ipc/mqueue.c:init_once",
        "block/bdev.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124048,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493480400,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493480400,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227044092,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227044092,
      "name": "inode_init_once",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287039856,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287039856,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273157758,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273157758,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942928,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942928,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880496,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880496,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934240,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934240,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void inode_init_once(struct inode * inode)
```

```json
{
  "name": "inode_init_once",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005360,
      "name": "inode_init_once",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init_inode",
        "fs/inode.c:init_once",
        "fs/block_dev.c:init_once",
        "fs/proc/inode.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/squashfs/super.c:init_once",
        "fs/hugetlbfs/inode.c:init_once",
        "fs/fat/inode.c:init_once",
        "fs/ecryptfs/main.c:inode_info_init_once",
        "fs/fuse/inode.c:fuse_inode_init_once",
        "ipc/mqueue.c:init_once",
        "drivers/dax/super.c:init_once",
        "net/socket.c:init_once"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005360,
      "name": "inode_init_once",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
