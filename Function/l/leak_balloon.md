# Function: <code>leak_balloon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840832,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:185",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify",
        "drivers/virtio/virtio_balloon.c:balloon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840832,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584171008,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:200",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171008,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584351408,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:200",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351408,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434336,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:195",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434336,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584842768,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:208",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584842768,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073632,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:208",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtballoon_oom_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073632,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585181872,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:245",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585181872,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585394352,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:233",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394352,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585535040,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535040,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251216,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:275",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251216,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586369216,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:275",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586369216,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586253984,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:275",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253984,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764704,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:275",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764704,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588042848,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:275",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042848,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589421792,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:268",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421792,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589720976,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:268",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720976,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590058432,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:273",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify",
        "drivers/virtio/virtio_balloon.c:update_balloon_size_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058432,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498191496,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498191496,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230958360,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230958360,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291431360,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291431360,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275971614,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275971614,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297072,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297072,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585249584,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585249584,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485440,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485440,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
unsigned int leak_balloon(struct virtio_balloon * vb, size_t num)
```

```json
{
  "name": "leak_balloon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585594400,
      "name": "leak_balloon",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:235",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594400,
      "name": "leak_balloon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
