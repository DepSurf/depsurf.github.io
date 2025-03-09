# Function: <code>of_find_backlight_by_node</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct backlight_device * of_find_backlight_by_node(struct device_node * node)
```

```json
{
  "name": "of_find_backlight_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497241124,
      "name": "of_find_backlight_by_node",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:592",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:of_find_backlight"
      ],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497240984,
      "name": "of_find_backlight_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct backlight_device * of_find_backlight_by_node(struct device_node * node)
```

```json
{
  "name": "of_find_backlight_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230426748,
      "name": "of_find_backlight_by_node",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:592",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:of_find_backlight"
      ],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230426620,
      "name": "of_find_backlight_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct backlight_device * of_find_backlight_by_node(struct device_node * node)
```

```json
{
  "name": "of_find_backlight_by_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291215424,
      "name": "of_find_backlight_by_node",
      "external": true,
      "loc": "drivers/video/backlight/backlight.c:592",
      "file": "drivers/video/backlight/backlight.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/backlight/backlight.c:of_find_backlight"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291215248,
      "name": "of_find_backlight_by_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct backlight_device * of_find_backlight_by_node(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct backlight_device * of_find_backlight_by_node(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct backlight_device * of_find_backlight_by_node(struct device_node * node)
```
</details>
</li>
</ul>
