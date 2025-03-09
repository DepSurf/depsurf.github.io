# Function: <code>usb_control_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585205984,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:131",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205984,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585598192,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:132",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598192,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585785760,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785760,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872304,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:134",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872304,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586312544,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:134",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586312544,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586569968,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586569968,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718912,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718912,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974080,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974080,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587173120,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587173120,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588023360,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_req_set_sel",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:hub_handle_remote_wakeup",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023360,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588072752,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_req_set_sel",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:hub_handle_remote_wakeup",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072752,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587955520,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_req_set_sel",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955520,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566432,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_req_set_sel",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566432,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589977152,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_req_set_sel",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589977152,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591570704,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591570704,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591992464,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:136",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:get_bMaxPacketSize0",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv",
        "drivers/usb/core/message.c:usb_control_msg_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591992464,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592732288,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:137",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:get_bMaxPacketSize0",
        "drivers/usb/core/hub.c:hub_port_debounce",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:check_port_resume_type",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_wait_reset",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/message.c:usb_control_msg_recv",
        "drivers/usb/core/message.c:usb_control_msg_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592732288,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500254528,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500254528,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232727356,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232727356,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293548704,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_enable_link_state",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293548704,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277168822,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_enable_link_state",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277168822,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879200,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879200,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820320,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820320,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587127680,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127680,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int usb_control_msg(struct usb_device * dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void * data, __u16 size, int timeout)
```

```json
{
  "name": "usb_control_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587234784,
      "name": "usb_control_msg",
      "external": true,
      "loc": "drivers/usb/core/message.c:135",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_set_device_initiated_lpm",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_hub_status",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_tt_work",
        "drivers/usb/core/hub.c:hub_ext_port_status",
        "drivers/usb/core/hub.c:set_port_feature",
        "drivers/usb/core/hub.c:usb_clear_port_feature",
        "drivers/usb/core/hub.c:clear_hub_feature",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_set_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_reset_configuration",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_clear_halt",
        "drivers/usb/core/message.c:usb_get_status",
        "drivers/usb/core/message.c:usb_set_isoch_delay",
        "drivers/usb/core/message.c:usb_get_string",
        "drivers/usb/core/message.c:usb_get_descriptor",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234784,
      "name": "usb_control_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
