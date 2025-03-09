# Function: <code>set_port_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151936,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:406",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151936,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585544352,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:408",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585544352,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585732256,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:411",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585732256,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819664,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:420",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:usb_hub_set_port_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819664,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586258912,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:420",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586258912,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586516304,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:423",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586516304,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664880,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:424",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664880,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919216,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:426",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919216,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587117664,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587117664,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587989923,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:430",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588049531,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:430",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587931753,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:437",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588541848,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:437",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589951459,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:437",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591535485,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:441",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591957408,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:441",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592697291,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:461",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500191576,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500191576,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232671340,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:set_port_led"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232671340,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293474080,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:set_port_led"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293474080,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277117802,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on",
        "drivers/usb/core/hub.c:set_port_led"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277117802,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586823744,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823744,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586765520,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765520,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072224,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072224,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```

```json
{
  "name": "set_port_feature",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587179600,
      "name": "set_port_feature",
      "external": false,
      "loc": "drivers/usb/core/hub.c:428",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:hub_port_disable",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:usb_set_lpm_timeout",
        "drivers/usb/core/hub.c:hub_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_power_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179600,
      "name": "set_port_feature",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int set_port_feature(struct usb_device * hdev, int port1, int feature)
```
</details>
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
