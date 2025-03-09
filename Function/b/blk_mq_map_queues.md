# Function: <code>blk_mq_map_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int blk_mq_map_queues(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202176,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:34",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202176,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int blk_mq_map_queues(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583256624,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:38",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_queue_map",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583256624,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int blk_mq_map_queues(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583435840,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:38",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583435840,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int blk_mq_map_queues(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647008,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:33",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647008,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583753808,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:34",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753808,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942896,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942896,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584046352,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584046352,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584442160,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_queue_map",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442160,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558976,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_queue_map",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558976,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584591776,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_queue_map",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584591776,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585006272,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585006272,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585721584,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721584,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586502544,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586502544,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
void blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586749872,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:18",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "drivers/block/virtio_blk.c:virtblk_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749872,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587022128,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:18",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "drivers/block/virtio_blk.c:virtblk_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues",
        "drivers/scsi/virtio_scsi.c:virtscsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022128,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495882304,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495882304,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229227316,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229227316,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290085552,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290085552,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275004352,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275004352,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584015088,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues",
        "drivers/nvme/host/pci.c:nvme_pci_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015088,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950912,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues",
        "drivers/nvme/host/pci.c:nvme_pci_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950912,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583998848,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998848,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int blk_mq_map_queues(struct blk_mq_queue_map * qmap)
```

```json
{
  "name": "blk_mq_map_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101200,
      "name": "blk_mq_map_queues",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:35",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq-virtio.c:blk_mq_virtio_map_queues",
        "block/blk-mq-rdma.c:blk_mq_rdma_map_queues",
        "drivers/scsi/scsi_lib.c:scsi_map_queues"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101200,
      "name": "blk_mq_map_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int blk_mq_map_queues(struct blk_mq_tag_set * set)
```
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_queue_map * qmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_tag_set * set</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
