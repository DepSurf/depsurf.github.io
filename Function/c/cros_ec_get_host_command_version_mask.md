# Function: <code>cros_ec_get_host_command_version_mask</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586690073,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:238",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586815473,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:288",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587299729,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:290",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587602717,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:292",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587730365,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:292",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012768,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:296",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012768,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588220464,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:297",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220464,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589094432,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:320",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094432,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589094160,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:363",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094160,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588983232,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:363",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588983232,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589694624,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:372",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589694624,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591201424,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:374",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201424,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592942096,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:446",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592942096,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593391856,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:446",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593391856,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594137120,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:446",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594137120,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501661288,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:297",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501661288,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234195356,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:297",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234195356,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587832160,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:297",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832160,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174944,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:297",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174944,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```

```json
{
  "name": "cros_ec_get_host_command_version_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588292832,
      "name": "cros_ec_get_host_command_version_mask",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:297",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292832,
      "name": "cros_ec_get_host_command_version_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device * ec_dev, u16 cmd, u32 * mask)
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
