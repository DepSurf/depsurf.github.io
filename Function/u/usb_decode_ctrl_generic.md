# Function: <code>usb_decode_ctrl_generic</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void usb_decode_ctrl_generic(char * str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength)
```

```json
{
  "name": "usb_decode_ctrl_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591496048,
      "name": "usb_decode_ctrl_generic",
      "external": false,
      "loc": "drivers/usb/common/debug.c:211",
      "file": "drivers/usb/common/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/common/debug.c:usb_decode_ctrl",
        "drivers/usb/common/debug.c:usb_decode_ctrl_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591496048,
      "name": "usb_decode_ctrl_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void usb_decode_ctrl_generic(char * str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength)
```

```json
{
  "name": "usb_decode_ctrl_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591917056,
      "name": "usb_decode_ctrl_generic",
      "external": false,
      "loc": "drivers/usb/common/debug.c:211",
      "file": "drivers/usb/common/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/common/debug.c:usb_decode_ctrl",
        "drivers/usb/common/debug.c:usb_decode_ctrl_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591917056,
      "name": "usb_decode_ctrl_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void usb_decode_ctrl_generic(char * str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength)
```

```json
{
  "name": "usb_decode_ctrl_generic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592656896,
      "name": "usb_decode_ctrl_generic",
      "external": false,
      "loc": "drivers/usb/common/debug.c:211",
      "file": "drivers/usb/common/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/common/debug.c:usb_decode_ctrl",
        "drivers/usb/common/debug.c:usb_decode_ctrl_standard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592656896,
      "name": "usb_decode_ctrl_generic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void usb_decode_ctrl_generic(char * str, size_t size, __u8 bRequestType, __u8 bRequest, __u16 wValue, __u16 wIndex, __u16 wLength)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
