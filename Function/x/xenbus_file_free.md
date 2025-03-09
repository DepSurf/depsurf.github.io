# Function: <code>xenbus_file_free</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486400,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:300",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486400,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896752,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:300",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896752,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585127904,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:300",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127904,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585238704,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:300",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238704,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585450944,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:303",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450944,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585591376,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585591376,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586314666,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586433290,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586317418,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586837130,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588122276,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589509412,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589810372,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590146644,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498257440,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498257440,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354000,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354000,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541776,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541776,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void xenbus_file_free(struct kref * kref)
```

```json
{
  "name": "xenbus_file_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585649760,
      "name": "xenbus_file_free",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_dev_frontend.c:339",
      "file": "drivers/xen/xenbus/xenbus_dev_frontend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649760,
      "name": "xenbus_file_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void xenbus_file_free(struct kref * kref)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void xenbus_file_free(struct kref * kref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xenbus_file_free(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xenbus_file_free(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xenbus_file_free(struct kref * kref)
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
void xenbus_file_free(struct kref * kref)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
