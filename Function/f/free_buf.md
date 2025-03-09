# Function: <code>free_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584180688,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:365",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:reclaim_dma_bufs",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:control_work_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180688,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584519712,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:371",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519712,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584701792,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:370",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701792,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584783232,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:370",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783232,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585203360,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:370",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585203360,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585439616,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:370",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439616,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585563072,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:370",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563072,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585782848,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782848,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585925552,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585925552,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661424,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_poll",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661424,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771344,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_poll",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771344,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652032,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_poll",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:wait_port_writable",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652032,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587200288,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:out_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:remove_port_data",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587200288,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588506256,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:358",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506256,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589947696,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:350",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589947696,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590256960,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:351",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590256960,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590597936,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:348",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_freeze",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:in_intr",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:unplug_port",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:port_fops_write",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590597936,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498755544,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498755544,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231372844,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231372844,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291911200,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291911200,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276254526,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_remove",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276254526,
      "name": "free_buf.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585686528,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585686528,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585547104,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547104,
      "name": "free_buf.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585876656,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876656,
      "name": "free_buf.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void free_buf(struct port_buffer * buf, bool can_sleep)
```

```json
{
  "name": "free_buf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585983824,
      "name": "free_buf",
      "external": false,
      "loc": "drivers/char/virtio_console.c:357",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:remove_vqs",
        "drivers/char/virtio_console.c:flush_bufs",
        "drivers/char/virtio_console.c:control_work_handler",
        "drivers/char/virtio_console.c:fill_queue",
        "drivers/char/virtio_console.c:port_fops_splice_write",
        "drivers/char/virtio_console.c:discard_port_data",
        "drivers/char/virtio_console.c:reclaim_dma_bufs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585983824,
      "name": "free_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_buf(struct port_buffer * buf, bool can_sleep)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void free_buf(struct port_buffer * buf, bool can_sleep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void free_buf(struct port_buffer * buf, bool can_sleep)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
