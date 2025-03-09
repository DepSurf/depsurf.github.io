# Function: <code>virtqueue_kick</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583823776,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:423",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_control_msg",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/virtio_net.c:try_fill_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823776,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584152192,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:593",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/virtio_net.c:try_fill_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152192,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584333632,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:593",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333632,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584413568,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:622",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413568,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584821392,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:621",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821392,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585050992,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:620",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_sgs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050992,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585157232,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1865",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157232,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585366640,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1870",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585366640,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585505376,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505376,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586230190,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227136,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586348542,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586347248,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231344,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1871",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231344,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1969",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592430084,
      "name": "virtqueue_kick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586739456,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1973",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594298067,
      "name": "virtqueue_kick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588013728,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2259",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596228433,
      "name": "virtqueue_kick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589387152,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2296",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/net/virtio_net.c:virtnet_send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596756122,
      "name": "virtqueue_kick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589685984,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2390",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_split",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:fill_readbuf",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req",
        "drivers/block/virtio_blk.c:virtio_queue_rq",
        "drivers/net/virtio_net.c:virtnet_send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597664496,
      "name": "virtqueue_kick.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590018288,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498160216,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498160216,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230923640,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230923640,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291389664,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291389664,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275942332,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275942332,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585267456,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585267456,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585219728,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219728,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585455776,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf",
        "drivers/scsi/virtio_scsi.c:virtscsi_kick_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455776,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool virtqueue_kick(struct virtqueue * vq)
```

```json
{
  "name": "virtqueue_kick",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585563952,
      "name": "virtqueue_kick",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1869",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx",
        "drivers/virtio/virtio_ring.c:virtqueue_add_inbuf",
        "drivers/virtio/virtio_ring.c:virtqueue_add_outbuf",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:add_inbuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563952,
      "name": "virtqueue_kick",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
