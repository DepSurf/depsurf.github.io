# Function: <code>usb_control_msg_send</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588077948,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:198",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074160,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587960866,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:198",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956944,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588571762,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:198",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567856,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589983581,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:198",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978752,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591578093,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:198",
      "file": "drivers/usb/core/message.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591572400,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591994160,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:198",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591994160,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```

```json
{
  "name": "usb_control_msg_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592734032,
      "name": "usb_control_msg_send",
      "external": true,
      "loc": "drivers/usb/core/message.c:199",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_isoch_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592734032,
      "name": "usb_control_msg_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int usb_control_msg_send(struct usb_device * dev, __u8 endpoint, __u8 request, __u8 requesttype, __u16 value, __u16 index, const void * driver_data, __u16 size, int timeout, gfp_t memflags)
```
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
