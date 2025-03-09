# Function: <code>cgwb_bdi_unregister</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580815964,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:703",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580906092,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:718",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581041818,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:699",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119466,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:702",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581184056,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:689",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581242713,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
void cgwb_bdi_unregister(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430240,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:711",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430240,
      "name": "cgwb_bdi_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
void cgwb_bdi_unregister(struct backing_dev_info * bdi)
```

```json
{
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473488,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:611",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473488,
      "name": "cgwb_bdi_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581495102,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:610",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581754618,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:633",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582134666,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:622",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582611866,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:749",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582820650,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:762",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582995354,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:757",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492641400,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226483700,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285958044,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272657164,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581211561,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581158297,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581202761,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
  "name": "cgwb_bdi_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581266121,
      "name": "cgwb_bdi_unregister",
      "external": false,
      "loc": "mm/backing-dev.c:712",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
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
void cgwb_bdi_unregister(struct backing_dev_info * bdi)
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
void cgwb_bdi_unregister(struct backing_dev_info * bdi)
```
</details>
</li>
</ul>
