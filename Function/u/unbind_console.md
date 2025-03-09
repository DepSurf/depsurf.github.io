# Function: <code>unbind_console</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int unbind_console(struct fb_info * fb_info)
```

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427792,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1707",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427792,
      "name": "unbind_console",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int unbind_console(struct fb_info * fb_info)
```

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524176,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1744",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524176,
      "name": "unbind_console",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584722676,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1672",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584858835,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585557657,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1670",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585691769,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1663",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585572073,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1661",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586046878,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1667",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587267430,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1687",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588508502,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1604",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588787190,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1500",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer"
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
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589086745,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:452",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unregister_framebuffer"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497246276,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230431508,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291223840,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275791166,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584810019,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584740787,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584811443,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unbind_console",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584916515,
      "name": "unbind_console",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbmem.c:1662",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:unlink_framebuffer"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int unbind_console(struct fb_info * fb_info)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int unbind_console(struct fb_info * fb_info)
```
</details>
</li>
</ul>
