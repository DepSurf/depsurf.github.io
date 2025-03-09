# Function: <code>virtio_check_driver_offered_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821056,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:108",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/block/virtio_blk.c:virtblk_ioctl",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_getgeo",
        "drivers/block/virtio_blk.c:init_vq",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/net/virtio_net.c:virtnet_send_command",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821056,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584147984,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:108",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:init_vq",
        "drivers/block/virtio_blk.c:virtblk_getgeo",
        "drivers/block/virtio_blk.c:virtblk_ioctl",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147984,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584328560,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:108",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328560,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584408512,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:103",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408512,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584815808,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:103",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815808,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585046272,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:103",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046272,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585154064,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:103",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154064,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585361424,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361424,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585500016,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500016,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586222176,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222176,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586340880,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586340880,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586225184,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586225184,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586731472,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:105",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731472,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588004624,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:106",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588004624,
      "name": "virtio_check_driver_offered_feature",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589375744,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:106",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375744,
      "name": "virtio_check_driver_offered_feature",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674384,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:106",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_attrs_are_visible",
        "drivers/block/virtio_blk.c:cache_type_store",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:init_vq",
        "drivers/block/virtio_blk.c:virtblk_getgeo",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/scsi/virtio_scsi.c:virtscsi_restore",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_queuecommand",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674384,
      "name": "virtio_check_driver_offered_feature",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590005264,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:106",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_attrs_are_visible",
        "drivers/block/virtio_blk.c:cache_type_store",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:virtblk_get_cache_mode",
        "drivers/block/virtio_blk.c:init_vq",
        "drivers/block/virtio_blk.c:virtblk_getgeo",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/scsi/virtio_scsi.c:virtscsi_restore",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_queuecommand",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate",
        "drivers/net/virtio_net.c:virtnet_validate_features",
        "drivers/net/virtio_net.c:virtnet_validate_features",
        "drivers/net/virtio_net.c:virtnet_validate_features",
        "drivers/net/virtio_net.c:virtnet_validate_features",
        "drivers/net/virtio_net.c:virtnet_validate_features",
        "drivers/net/virtio_net.c:virtnet_validate_features",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_find_vqs",
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_xdp_set",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_send_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590005264,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498155480,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe",
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498155480,
      "name": "virtio_check_driver_offered_feature",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230920180,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230920180,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291382672,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291382672,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275939370,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275939370,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585262096,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585262096,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585214720,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585214720,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585450416,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_restore",
        "drivers/scsi/virtio_scsi.c:virtscsi_remove",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_probe",
        "drivers/scsi/virtio_scsi.c:virtscsi_queuecommand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450416,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void virtio_check_driver_offered_feature(const struct virtio_device * vdev, unsigned int fbit)
```

```json
{
  "name": "virtio_check_driver_offered_feature",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585558656,
      "name": "virtio_check_driver_offered_feature",
      "external": true,
      "loc": "drivers/virtio/virtio.c:104",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:init_vqs",
        "drivers/virtio/virtio_balloon.c:virtballoon_changed",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585558656,
      "name": "virtio_check_driver_offered_feature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
