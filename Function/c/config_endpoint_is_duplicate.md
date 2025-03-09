# Function: <code>config_endpoint_is_duplicate</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool config_endpoint_is_duplicate(struct usb_host_config * config, int inum, int asnum, struct usb_endpoint_descriptor * d)
```

```json
{
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588045008,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588045008,
      "name": "config_endpoint_is_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
bool config_endpoint_is_duplicate(struct usb_host_config * config, int inum, int asnum, struct usb_endpoint_descriptor * d)
```

```json
{
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093232,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093232,
      "name": "config_endpoint_is_duplicate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277188548,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
  "name": "config_endpoint_is_duplicate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "config_endpoint_is_duplicate",
      "external": false,
      "loc": "drivers/usb/core/config.c:224",
      "file": "drivers/usb/core/config.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/config.c:usb_parse_endpoint"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool config_endpoint_is_duplicate(struct usb_host_config * config, int inum, int asnum, struct usb_endpoint_descriptor * d)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool config_endpoint_is_duplicate(struct usb_host_config * config, int inum, int asnum, struct usb_endpoint_descriptor * d)
```
</details>
</li>
</ul>
