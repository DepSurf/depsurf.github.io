# Function: <code>init_once</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101776,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:370",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581233808,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:524",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581438448,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:86",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581650624,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:959",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581941616,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:959",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581946640,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:38",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581976832,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:662",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582173664,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:342",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582605824,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:150",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586175552,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:283",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101776,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581233808,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071581438448,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581650624,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071581941616,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581946640,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071581976832,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582173664,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582605824,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586175552,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267456,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:378",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581399824,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:610",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581622112,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:86",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581865936,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:984",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582138384,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:410",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582151072,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:966",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582158112,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:38",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582188976,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:745",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582389824,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:340",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582850912,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:151",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586596208,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:283",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267456,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581399824,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581622112,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581865936,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582138384,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582151072,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582158112,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582188976,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582389824,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582850912,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586596208,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345328,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:380",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581478160,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:862",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581710464,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:85",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581954816,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:989",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582228128,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:410",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582240528,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:964",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582247520,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:38",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582278416,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:745",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481984,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:340",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582946944,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:151",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586780592,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:283",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345328,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581478160,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071581710464,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581954816,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582228128,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582240528,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582247520,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582278416,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582481984,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582946944,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586780592,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400704,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:378",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581533888,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:756",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581764704,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:86",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582170000,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1031",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582313328,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:410",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582326560,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1023",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582332448,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:38",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582362944,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:745",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582562720,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:343",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582997136,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:151",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585387152,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:537",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586902240,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:283",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400704,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581533888,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071581764704,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582170000,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582313328,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582326560,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582332448,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582362944,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582562720,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582997136,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585387152,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071586902240,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542320,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:378",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581676416,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:746",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914304,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:87",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582318576,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1032",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582462496,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:410",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582476112,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1023",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582483008,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582513728,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:745",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582715200,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:343",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583161216,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:151",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585816592,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:566",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587394032,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:283",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542320,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581676416,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071581914304,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582318576,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071582462496,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582476112,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582483008,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582513728,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071582715200,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583161216,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585816592,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071587394032,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697712,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:384",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581839488,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:747",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582098864,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:89",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582507536,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1071",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582653296,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582666864,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1044",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582674144,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582703376,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:764",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582910016,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:360",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583366720,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:156",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586061152,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:592",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587693968,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:277",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697712,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581839488,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582098864,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582507536,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071582653296,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582666864,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582674144,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582703376,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582910016,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583366720,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586061152,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587693968,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784064,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:384",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581926864,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:786",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582193200,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:87",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582608064,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1125",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582757024,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582768752,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1054",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582776016,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582807104,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:760",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583018544,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:360",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583485472,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:157",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586205568,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:591",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587828064,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:275",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784064,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581926864,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582193200,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582608064,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071582757024,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582768752,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582776016,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582807104,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583018544,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583485472,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586205568,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587828064,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902240,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:397",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582064464,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582356512,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582780224,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1138",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582931232,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:398",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582944192,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582950096,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582981920,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:755",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583199792,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:416",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583671568,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586442640,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588130384,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902240,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582064464,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582356512,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582780224,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071582931232,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582944192,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582950096,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582981920,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583199792,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583671568,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586442640,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588130384,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974480,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582142128,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582455408,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582883472,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583038192,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583050848,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583056752,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583088160,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583305568,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583778576,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586590576,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588335520,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974480,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582142128,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582455408,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582883472,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071583038192,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583050848,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583056752,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583088160,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583305568,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583778576,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586590576,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588335520,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206976,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:402",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582378624,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:779",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582749632,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:88",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583195952,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1181",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583353840,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583369008,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1157",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583375808,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583407456,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583636784,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:475",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584169120,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587376432,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:680",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589195024,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:277",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206976,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582378624,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582749632,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583195952,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583353840,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583369008,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583375808,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583407456,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583636784,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584169120,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071587376432,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071589195024,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254448,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:403",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582434000,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:814",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582821840,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:88",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583291440,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1345",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583470160,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:410",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583484992,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1158",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583491744,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583522992,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583757200,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:475",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584288240,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:161",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587437120,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:688",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589193168,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:277",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254448,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582434000,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582821840,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583291440,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583470160,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583484992,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583491744,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583522992,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583757200,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584288240,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071587437120,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071589193168,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280352,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:403",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582460944,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:820",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582850576,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:88",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583315568,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1354",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583492432,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:410",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583506448,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1152",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583513824,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583546144,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583781328,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:475",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584322080,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:161",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587318896,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:688",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589086688,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:277",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280352,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582460944,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582850576,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583315568,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583492432,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583506448,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583513824,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583546144,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583781328,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584322080,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071587318896,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071589086688,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598400,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:407",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583183632,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:88",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583658784,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1361",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583847040,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:494",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583861152,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1153",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583869296,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583904176,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:768",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584143504,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:478",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584709216,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:161",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584889696,
      "name": "init_once",
      "external": false,
      "loc": "block/bdev.c:418",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587886128,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:643",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589803824,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:327",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598400,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071583183632,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583658784,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071583847040,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583861152,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583869296,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583904176,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071584143504,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584709216,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584889696,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587886128,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071589803824,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583130416,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:431",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583677760,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:88",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584227840,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1401",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584415984,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:528",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584432176,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1204",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584442592,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584481712,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:772",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584743984,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:490",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585382880,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:161",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585588384,
      "name": "init_once",
      "external": false,
      "loc": "block/bdev.c:422",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589237440,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:452",
      "file": "drivers/dax/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591322480,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:328",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130416,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071583677760,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584227840,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071584415984,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584432176,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584442592,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584481712,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584743984,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585382880,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071585588384,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071589237440,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591322480,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700672,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:430",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584286192,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:86",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584869984,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1396",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585074592,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:589",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585093824,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1280",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585104992,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585146432,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585438576,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:490",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586134480,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:161",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586354848,
      "name": "init_once",
      "external": false,
      "loc": "block/bdev.c:421",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590795584,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:517",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593076288,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:328",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700672,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584286192,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584869984,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585074592,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585093824,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585104992,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585146432,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585438576,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586134480,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071586354848,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590795584,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071593076288,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918544,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:430",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584515952,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:86",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585095008,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1462",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585304064,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:606",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585323312,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1275",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585334240,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585375584,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585669328,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:490",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586372336,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:156",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586601488,
      "name": "init_once",
      "external": false,
      "loc": "block/bdev.c:343",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591137120,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:520",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593527808,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:330",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918544,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584515952,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585095008,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585304064,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585323312,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585334240,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585375584,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585669328,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586372336,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071586601488,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591137120,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071593527808,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124352,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:431",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584746896,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:83",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585326720,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585538032,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:606",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585558048,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1295",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585568912,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585610320,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:772",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585833760,
      "name": "init_once",
      "external": false,
      "loc": "fs/tracefs/inode.c:716",
      "file": "fs/tracefs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585916112,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:490",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586870800,
      "name": "init_once",
      "external": false,
      "loc": "block/bdev.c:332",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591482816,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:521",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594299648,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:332",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124352,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584746896,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585326720,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585538032,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585558048,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585568912,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585610320,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585833760,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585916112,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586870800,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591482816,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071594299648,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493480560,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493691944,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494068160,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494535560,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494734136,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494748776,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494755176,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494794536,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495043592,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495580688,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499473744,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501829056,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493480560,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336493691944,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336494068160,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336494535560,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446603336494734136,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336494748776,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336494755176,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336494794536,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336495043592,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446603336495580688,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446603336499473744,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336501829056,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227044244,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227219848,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227523004,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228000676,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228170056,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228180464,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228216184,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228446712,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228942468,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231948276,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234610852,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227044244,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 3227219848,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 3227523004,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3228000676,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 3228170056,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3228180464,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3228216184,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3228446712,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 3228942468,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3231948276,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3234610852,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287040064,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287292352,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287729248,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288348800,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288556784,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288578528,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288585728,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288633408,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288937008,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289678608,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292752256,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295232736,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287040064,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 13835058055287292352,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 13835058055287729248,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 13835058055288348800,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 13835058055288556784,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 13835058055288578528,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 13835058055288585728,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 13835058055288633408,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 13835058055288937008,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 13835058055289678608,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 13835058055292752256,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055295232736,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273157914,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273310408,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273562108,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273942682,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274081276,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274093390,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274097790,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274124654,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274319834,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274747108,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276693774,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278175550,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273157914,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446743936273310408,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446743936273562108,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446743936273942682,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446743936274081276,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446743936274093390,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446743936274097790,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936274124654,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446743936274319834,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446743936274747108,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936276693774,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936278175550,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943216,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582110864,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582424144,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582852208,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583006928,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583019584,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583025488,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583056896,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583274304,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583747312,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586281056,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587942304,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943216,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582110864,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582424144,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582852208,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071583006928,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583019584,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583025488,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583056896,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583274304,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583747312,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586281056,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587942304,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880784,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582048304,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582361312,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582789360,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582944080,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582956736,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582962640,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582994048,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583211440,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583684368,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586118544,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587655408,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880784,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582048304,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582361312,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582789360,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071582944080,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582956736,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582962640,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582994048,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583211440,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583684368,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586118544,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587655408,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934528,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582101344,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582414624,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582841088,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582995536,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583008192,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583014096,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583045504,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583258336,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583731088,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586538544,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588274080,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934528,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582101344,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582414624,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582841088,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071582995536,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583008192,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583014096,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583045504,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583258336,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583731088,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586538544,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588274080,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
void init_once(void * foo)
```

```json
{
  "name": "init_once",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005648,
      "name": "init_once",
      "external": false,
      "loc": "fs/inode.c:401",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582174208,
      "name": "init_once",
      "external": false,
      "loc": "fs/block_dev.c:783",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582494064,
      "name": "init_once",
      "external": false,
      "loc": "fs/proc/inode.c:80",
      "file": "fs/proc/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582928640,
      "name": "init_once",
      "external": false,
      "loc": "fs/ext4/super.c:1146",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583084672,
      "name": "init_once",
      "external": false,
      "loc": "fs/squashfs/super.c:411",
      "file": "fs/squashfs/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583097616,
      "name": "init_once",
      "external": false,
      "loc": "fs/hugetlbfs/inode.c:1078",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583103264,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/cache.c:39",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583135920,
      "name": "init_once",
      "external": false,
      "loc": "fs/fat/inode.c:767",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583355056,
      "name": "init_once",
      "external": false,
      "loc": "ipc/mqueue.c:415",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583831936,
      "name": "init_once",
      "external": false,
      "loc": "security/integrity/iint.c:153",
      "file": "security/integrity/iint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586650800,
      "name": "init_once",
      "external": false,
      "loc": "drivers/dax/super.c:652",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588409392,
      "name": "init_once",
      "external": false,
      "loc": "net/socket.c:263",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005648,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071582174208,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071582494064,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582928640,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071583084672,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583097616,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583103264,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071583135920,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583355056,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583831936,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586650800,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588409392,
      "name": "init_once",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
