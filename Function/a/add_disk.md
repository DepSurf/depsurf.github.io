# Function: <code>add_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_disk(struct gendisk * disk)
```

```json
{
  "name": "add_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582822320,
      "name": "add_disk",
      "external": true,
      "loc": "block/genhd.c:583",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/brd.c:brd_init",
        "drivers/block/brd.c:brd_probe",
        "drivers/block/loop.c:loop_add",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/sd.c:sd_probe_async",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582822320,
      "name": "add_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595467210,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:417",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/brd.c:brd_init",
        "drivers/block/brd.c:brd_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584894905,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:417",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141910,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:417",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586201197,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:417",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585085161,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:408",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344454,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:408",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586405682,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:408",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584976223,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:402",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585167966,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:402",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586444735,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:402",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586509196,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:402",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585397497,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585595664,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586911700,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586976685,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:394",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585641126,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:397",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585840100,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:397",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587206652,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:397",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585770528,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:420",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585974654,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:420",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587386841,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:420",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586001905,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586217548,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587658303,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586149074,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586365596,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862479,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586906379,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:294",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134044,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:294",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588712000,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:294",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586991297,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:239",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587219773,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:239",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588739353,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:239",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586872095,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:210",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108110,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:210",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588621324,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:210",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587681254,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:210",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589298569,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:210",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589377340,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:210",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589028529,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:761",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590764618,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:761",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590852968,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:761",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590556756,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:749",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592468409,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:749",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592543718,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:749",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590885188,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:733",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592890650,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:733",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592974874,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:733",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591229252,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:710",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593639559,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:710",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593724858,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/blkdev.h:710",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_setup_md_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498942380,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499206912,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501081828,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231513752,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 3231740756,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3233594400,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292080004,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292416992,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294585196,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276326738,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276499828,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277815620,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585909442,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586127484,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587493455,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585972092,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587261615,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586099090,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586313564,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587818623,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_disk",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586207698,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425228,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587928543,
      "name": "add_disk",
      "external": false,
      "loc": "include/linux/genhd.h:427",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void add_disk(struct gendisk * disk)
```
</details>
</li>
</ul>
