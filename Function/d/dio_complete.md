# Function: <code>dio_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio * dio, loff_t offset, ssize_t ret, bool is_async)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243648,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:227",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243648,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, bool is_async)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409984,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:228",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409984,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, bool is_async)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490720,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:228",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490720,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, bool is_async)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545600,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:228",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545600,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688528,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:234",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688528,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581856384,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856384,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941072,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941072,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078688,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:256",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078688,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582156128,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156128,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391568,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:236",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391568,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445568,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:236",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445568,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472368,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:236",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472368,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784512,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:236",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784512,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583337072,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:235",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337072,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921136,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:234",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921136,
      "name": "dio_complete",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154592,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:245",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154592,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368768,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:245",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368768,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493709808,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493709808,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227236164,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227236164,
      "name": "dio_complete",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287314576,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287314576,
      "name": "dio_complete",
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273324340,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273324340,
      "name": "dio_complete",
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124864,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124864,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582062304,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582062304,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115344,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115344,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
ssize_t dio_complete(struct dio * dio, ssize_t ret, unsigned int flags)
```

```json
{
  "name": "dio_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188304,
      "name": "dio_complete",
      "external": false,
      "loc": "fs/direct-io.c:255",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_end_aio",
        "fs/direct-io.c:dio_aio_complete_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188304,
      "name": "dio_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>dio, offset, ret, is_async</code> ➡️ <code>dio, ret, is_async</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_async</code>
</li>
</ul>
</details>
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
