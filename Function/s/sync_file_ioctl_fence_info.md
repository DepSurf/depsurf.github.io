# Function: <code>sync_file_ioctl_fence_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585125336,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:313",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585314824,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:389",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585403328,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:404",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585403328,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585832880,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:406",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585832880,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586079936,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:406",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586079936,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586224208,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:406",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586224208,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586467904,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467904,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586615792,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586615792,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410928,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410928,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587480128,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:397",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480128,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361584,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361584,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587928528,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587928528,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589281088,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:389",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589281088,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 930
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590842912,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:282",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590842912,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591184992,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:282",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591184992,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591531248,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:279",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591531248,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499505264,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499505264,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231974836,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231974836,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292792800,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292792800,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276716966,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276716966,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586306272,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306272,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586147648,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586147648,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563760,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563760,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
```

```json
{
  "name": "sync_file_ioctl_fence_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676048,
      "name": "sync_file_ioctl_fence_info",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:398",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676048,
      "name": "sync_file_ioctl_fence_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
long int sync_file_ioctl_fence_info(struct sync_file * sync_file, long unsigned int arg)
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
