# Function: <code>flush_scrollback</code>

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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584650584,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:632",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585063027,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:634",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585297865,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:634",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585417034,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:938",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585628374,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:938",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585773110,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
void flush_scrollback(struct vc_data * vc)
```

```json
{
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506000,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:945",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:csi_J"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506000,
      "name": "flush_scrollback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void flush_scrollback(struct vc_data * vc)
```

```json
{
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618080,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:951",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:csi_J"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618080,
      "name": "flush_scrollback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586504278,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:951",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587040292,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:947",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588342603,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:947",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589767115,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:947",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590071974,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:896",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590411142,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:895",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498490408,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231144416,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291680952,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276121732,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585534102,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585403926,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585723510,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
  "name": "flush_scrollback",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585831542,
      "name": "flush_scrollback",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:939",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:csi_J"
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
void flush_scrollback(struct vc_data * vc)
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
void flush_scrollback(struct vc_data * vc)
```
</details>
</li>
</ul>
