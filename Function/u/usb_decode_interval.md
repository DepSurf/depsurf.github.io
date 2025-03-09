# Function: <code>usb_decode_interval</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```

```json
{
  "name": "usb_decode_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587900192,
      "name": "usb_decode_interval",
      "external": true,
      "loc": "drivers/usb/common/common.c:211",
      "file": "drivers/usb/common/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/endpoint.c:interval_show",
        "drivers/usb/core/devices.c:usb_dump_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900192,
      "name": "usb_decode_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```

```json
{
  "name": "usb_decode_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_decode_interval",
      "external": true,
      "loc": "drivers/usb/common/common.c:231",
      "file": "drivers/usb/common/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/endpoint.c:interval_show",
        "drivers/usb/core/devices.c:usb_dump_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592555935,
      "name": "usb_decode_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071588509712,
      "name": "usb_decode_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```

```json
{
  "name": "usb_decode_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_decode_interval",
      "external": true,
      "loc": "drivers/usb/common/common.c:231",
      "file": "drivers/usb/common/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/endpoint.c:interval_show",
        "drivers/usb/core/devices.c:usb_dump_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594435416,
      "name": "usb_decode_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071589916336,
      "name": "usb_decode_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```

```json
{
  "name": "usb_decode_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_decode_interval",
      "external": true,
      "loc": "drivers/usb/common/common.c:231",
      "file": "drivers/usb/common/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/endpoint.c:interval_show",
        "drivers/usb/core/devices.c:usb_dump_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596271186,
      "name": "usb_decode_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071591495808,
      "name": "usb_decode_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```

```json
{
  "name": "usb_decode_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_decode_interval",
      "external": true,
      "loc": "drivers/usb/common/common.c:231",
      "file": "drivers/usb/common/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/endpoint.c:interval_show",
        "drivers/usb/core/devices.c:usb_dump_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596800985,
      "name": "usb_decode_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071591916816,
      "name": "usb_decode_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```

```json
{
  "name": "usb_decode_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_decode_interval",
      "external": true,
      "loc": "drivers/usb/common/common.c:232",
      "file": "drivers/usb/common/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/endpoint.c:interval_show",
        "drivers/usb/core/devices.c:usb_dump_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597724591,
      "name": "usb_decode_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071592656656,
      "name": "usb_decode_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
unsigned int usb_decode_interval(const struct usb_endpoint_descriptor * epd, enum usb_device_speed speed)
```
</details>
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
