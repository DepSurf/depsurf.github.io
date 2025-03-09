# Function: <code>virtqueue_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823616,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:598",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb",
        "drivers/net/virtio_net.c:virtnet_busy_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823616,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584151058,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:784",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_busy_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151008,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584331698,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:786",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331648,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584411906,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:829",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411856,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584819312,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:828",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584819312,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049760,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:827",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049760,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585157568,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1954",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585157568,
      "name": "virtqueue_poll",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585365088,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1960",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585365088,
      "name": "virtqueue_poll",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585503824,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503824,
      "name": "virtqueue_poll",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586227236,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb",
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586225424,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586347348,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb",
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345584,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586232628,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1961",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb",
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586229296,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2068",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592428731,
      "name": "virtqueue_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071586734928,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2072",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594297857,
      "name": "virtqueue_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071588012384,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2358",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596228223,
      "name": "virtqueue_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589384640,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2389",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596755807,
      "name": "virtqueue_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589682736,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:2483",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb",
        "drivers/net/virtio_net.c:virtnet_poll_tx",
        "drivers/net/virtio_net.c:virtnet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597664139,
      "name": "virtqueue_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071590014800,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498159736,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498159736,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230923200,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230923200,
      "name": "virtqueue_poll",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291389296,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291389296,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275941914,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275941914,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585265904,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585265904,
      "name": "virtqueue_poll",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585218192,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218192,
      "name": "virtqueue_poll",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585454224,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454224,
      "name": "virtqueue_poll",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool virtqueue_poll(struct virtqueue * _vq, unsigned int last_used_idx)
```

```json
{
  "name": "virtqueue_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585562400,
      "name": "virtqueue_poll",
      "external": true,
      "loc": "drivers/virtio/virtio_ring.c:1959",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_enable_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562400,
      "name": "virtqueue_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
