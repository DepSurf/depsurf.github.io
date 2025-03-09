# Function: <code>fb_deferred_io_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fb_deferred_io_fault(struct vm_area_struct * vma, struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583512112,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512112,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int fb_deferred_io_fault(struct vm_area_struct * vma, struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583833088,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833088,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int fb_deferred_io_fault(struct vm_area_struct * vma, struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583972336,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972336,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020816,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020816,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236752,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236752,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457264,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071584458054,
      "name": "fb_deferred_io_fault.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553792,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071584554582,
      "name": "fb_deferred_io_fault.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751648,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584752431,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584886432,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584887215,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585583312,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071585584451,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716208,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071591424025,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585596640,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071591365528,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072496,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071592396455,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:94",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587295440,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    },
    {
      "addr": 18446744071594261238,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588535776,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:94",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535776,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588815296,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:94",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815296,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589108176,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:94",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108176,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497283576,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497283576,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230460036,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230460036,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291264576,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291264576,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275815366,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275815366,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837616,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584838399,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584767440,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584768223,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839040,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584839823,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault * vmf)
```

```json
{
  "name": "fb_deferred_io_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fb_deferred_io_fault",
      "external": false,
      "loc": "drivers/video/fbdev/core/fb_defio.c:40",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584944112,
      "name": "fb_deferred_io_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584944890,
      "name": "fb_deferred_io_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, vmf</code> ➡️ <code>vmf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
