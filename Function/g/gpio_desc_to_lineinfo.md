# Function: <code>gpio_desc_to_lineinfo</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpioline_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585191744,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1195",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:gpio_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585191744,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1890",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372896,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    },
    {
      "addr": 18446744071591389187,
      "name": "gpio_desc_to_lineinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1891",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257264,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    },
    {
      "addr": 18446744071591331627,
      "name": "gpio_desc_to_lineinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1891",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713568,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    },
    {
      "addr": 18446744071592354844,
      "name": "gpio_desc_to_lineinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:2082",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883600,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 647
    },
    {
      "addr": 18446744071594216989,
      "name": "gpio_desc_to_lineinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033504,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:2236",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033504,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308176,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:2233",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308176,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpio_v2_line_info * info)
```

```json
{
  "name": "gpio_desc_to_lineinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588612192,
      "name": "gpio_desc_to_lineinfo",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:2300",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612192,
      "name": "gpio_desc_to_lineinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void gpio_desc_to_lineinfo(struct gpio_desc * desc, struct gpioline_info * info)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct gpioline_info * info</code> ➡️ <code>struct gpio_v2_line_info * info</code>
</li>
</ul>
</details>
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
