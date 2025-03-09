# Function: <code>psp_send_i2c_req</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int psp_send_i2c_req(enum psp_i2c_req_type i2c_req_type)
```

```json
{
  "name": "psp_send_i2c_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psp_send_i2c_req",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-amdpsp.c:197",
      "file": "drivers/i2c/busses/i2c-designware-amdpsp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_release_i2c_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_acquire_i2c_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590617776,
      "name": "psp_send_i2c_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071594515543,
      "name": "psp_send_i2c_req.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int psp_send_i2c_req(enum psp_i2c_req_type i2c_req_type)
```

```json
{
  "name": "psp_send_i2c_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592279280,
      "name": "psp_send_i2c_req",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-amdpsp.c:200",
      "file": "drivers/i2c/busses/i2c-designware-amdpsp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_release_i2c_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_acquire_i2c_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_release_i2c_bus_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592279280,
      "name": "psp_send_i2c_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int psp_send_i2c_req(enum psp_i2c_req_type i2c_req_type)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int psp_send_i2c_req(enum psp_i2c_req_type i2c_req_type)
```
</details>
</li>
</ul>
