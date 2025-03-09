# Function: <code>bgpio_line2mask</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip * gc, unsigned int line)
```

```json
{
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586917205,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
      ],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914192,
      "name": "bgpio_line2mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071594218094,
      "name": "bgpio_line2mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip * gc, unsigned int line)
```

```json
{
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588072181,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
      ],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069072,
      "name": "bgpio_line2mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071596206454,
      "name": "bgpio_line2mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip * gc, unsigned int line)
```

```json
{
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588346725,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
      ],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343616,
      "name": "bgpio_line2mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071596731496,
      "name": "bgpio_line2mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip * gc, unsigned int line)
```

```json
{
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641333,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:124",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
      ],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_get_dir",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638016,
      "name": "bgpio_line2mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071597639924,
      "name": "bgpio_line2mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496763540,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
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
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230038424,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
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
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290849124,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
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
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275503832,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
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
  "name": "bgpio_line2mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584521972,
      "name": "bgpio_line2mask",
      "external": false,
      "loc": "drivers/gpio/gpio-mmio.c:125",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_dir_out",
        "drivers/gpio/gpio-mmio.c:bgpio_dir_in",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks",
        "drivers/gpio/gpio-mmio.c:bgpio_set_set",
        "drivers/gpio/gpio-mmio.c:bgpio_set_with_clear",
        "drivers/gpio/gpio-mmio.c:bgpio_set",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be",
        "drivers/gpio/gpio-mmio.c:bgpio_get",
        "drivers/gpio/gpio-mmio.c:bgpio_get_set"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
long unsigned int bgpio_line2mask(struct gpio_chip * gc, unsigned int line)
```
</details>
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
