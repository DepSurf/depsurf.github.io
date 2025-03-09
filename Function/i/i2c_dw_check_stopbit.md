# Function: <code>i2c_dw_check_stopbit</code>

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
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_check_stopbit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588490080,
      "name": "i2c_dw_check_stopbit",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:255",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490080,
      "name": "i2c_dw_check_stopbit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_check_stopbit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589158672,
      "name": "i2c_dw_check_stopbit",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:255",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589158672,
      "name": "i2c_dw_check_stopbit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_check_stopbit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_check_stopbit",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:255",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590611504,
      "name": "i2c_dw_check_stopbit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071594515121,
      "name": "i2c_dw_check_stopbit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_check_stopbit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592272704,
      "name": "i2c_dw_check_stopbit",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:255",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592272704,
      "name": "i2c_dw_check_stopbit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_check_stopbit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592698128,
      "name": "i2c_dw_check_stopbit",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:255",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698128,
      "name": "i2c_dw_check_stopbit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_check_stopbit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593443024,
      "name": "i2c_dw_check_stopbit",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:256",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk",
        "drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593443024,
      "name": "i2c_dw_check_stopbit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int i2c_dw_check_stopbit(struct dw_i2c_dev * dev)
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
