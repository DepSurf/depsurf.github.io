# Function: <code>virtqueue_get_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583824928,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:477",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_control_msg",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824928,
      "name": "virtqueue_get_buf",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584152736,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:663",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152736,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584333248,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:663",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333248,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584413936,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413936,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584821168,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:757",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584821168,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585051840,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:756",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585051840,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159968,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1899",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159968,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585377408,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1905",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585377408,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585517888,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517888,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586229072,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_poll",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:discard_port_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229072,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586346688,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:get_free_page_and_send",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_poll",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:discard_port_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346688,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231040,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1906",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_poll",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:discard_port_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231040,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2004",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592430064,
      "name": "virtqueue_get_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586739376,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2008",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594298046,
      "name": "virtqueue_get_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588013632,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2294",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596228412,
      "name": "virtqueue_get_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589387040,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2331",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req",
        "drivers/block/virtio_blk.c:virtblk_poll",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_event_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_req_done",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:virtnet_xdp_xmit",
        "drivers/net/virtio_net.c:free_old_xmit_skbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596756101,
      "name": "virtqueue_get_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589685872,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2425",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:virtballoon_free_page_report",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_read",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req",
        "drivers/block/virtio_blk.c:virtblk_poll",
        "drivers/block/virtio_blk.c:virtblk_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_mq_poll",
        "drivers/scsi/virtio_scsi.c:virtscsi_event_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done",
        "drivers/scsi/virtio_scsi.c:virtscsi_req_done",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_xdp_xmit",
        "drivers/net/virtio_net.c:free_old_xmit_skbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597664433,
      "name": "virtqueue_get_buf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590017936,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498164720,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/iommu/virtio-iommu.c:viommu_event_handler",
        "drivers/iommu/virtio-iommu.c:__viommu_sync_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498164720,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230928736,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230928736,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291408016,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291408016,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275946582,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275946582,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279968,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279968,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585232432,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232432,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585468288,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/scsi/virtio_scsi.c:virtscsi_vq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468288,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void * virtqueue_get_buf(struct virtqueue * _vq, unsigned int * len)
```

```json
{
  "name": "virtqueue_get_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585576464,
      "name": "virtqueue_get_buf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1904",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576464,
      "name": "virtqueue_get_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
