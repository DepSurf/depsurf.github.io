# Function: <code>virtqueue_add_outbuf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583825984,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:311",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/char/virtio_console.c:__send_control_msg",
        "drivers/net/virtio_net.c:start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825984,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155104,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:481",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/net/virtio_net.c:start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155104,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335680,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:481",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335680,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416800,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:486",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416800,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584824336,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:485",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584824336,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 821
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585053920,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:484",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053920,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585164912,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1754",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:report_free_page_func",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585164912,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585371200,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1759",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371200,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1678
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585509824,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509824,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2301
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233680,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233680,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586352064,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586352064,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235104,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1760",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235104,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1858",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592430819,
      "name": "virtqueue_add_outbuf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586743888,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1862",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594298965,
      "name": "virtqueue_add_outbuf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588019312,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2148",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596229595,
      "name": "virtqueue_add_outbuf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589395216,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2185",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/net/virtio_net.c:xmit_skb",
        "drivers/net/virtio_net.c:__virtnet_xdp_xmit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596757358,
      "name": "virtqueue_add_outbuf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589694560,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2262",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port",
        "drivers/net/virtio_net.c:xmit_skb",
        "drivers/net/virtio_net.c:__virtnet_xdp_xmit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597665755,
      "name": "virtqueue_add_outbuf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071590027504,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498169080,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498169080,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1804
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230935252,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230935252,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2692
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291396208,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291396208,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3220
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275950540,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275950540,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2064
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271904,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271904,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2301
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585224368,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224368,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2301
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585460224,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585460224,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2301
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
int virtqueue_add_outbuf(struct virtqueue * vq, struct scatterlist * sg, unsigned int num, void * data, gfp_t gfp)
```

```json
{
  "name": "virtqueue_add_outbuf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585568400,
      "name": "virtqueue_add_outbuf",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1758",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:update_balloon_stats_func",
        "drivers/virtio/virtio_balloon.c:tell_host",
        "drivers/char/virtio_console.c:__send_to_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568400,
      "name": "virtqueue_add_outbuf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2301
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
