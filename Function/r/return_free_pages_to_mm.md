# Function: <code>return_free_pages_to_mm</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585183424,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:383",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585183424,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585396736,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:371",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396736,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537056,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537056,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586253808,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:413",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253808,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586371728,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:410",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371728,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586257760,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:410",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257760,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768336,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:410",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768336,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588046423,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:410",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588040432,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589425063,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:403",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418864,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589724215,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:403",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718064,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590062199,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:412",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055712,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498193776,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498193776,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230954200,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230954200,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291433968,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291433968,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275975362,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275975362,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585299088,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299088,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585251584,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585251584,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585487456,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487456,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```

```json
{
  "name": "return_free_pages_to_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585590320,
      "name": "return_free_pages_to_mm",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:373",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:remove_common",
        "drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan",
        "drivers/virtio/virtio_balloon.c:report_free_page_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590320,
      "name": "return_free_pages_to_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon * vb, long unsigned int num_to_return)
```
</details>
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
