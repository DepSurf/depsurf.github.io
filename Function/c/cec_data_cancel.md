# Function: <code>cec_data_cancel</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587251040,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:357",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251040,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587518896,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518896,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587721888,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721888,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500898912,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500898912,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233417528,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233417528,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294354640,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294354640,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277677878,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277677878,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587362832,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587362832,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131056,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131056,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587678032,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587678032,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```

```json
{
  "name": "cec_data_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587784416,
      "name": "cec_data_cancel",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:370",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/media/cec/cec-adap.c:cec_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587784416,
      "name": "cec_data_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void cec_data_cancel(struct cec_data * data, u8 tx_status)
```
</details>
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
void cec_data_cancel(struct cec_data * data, u8 tx_status)
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
