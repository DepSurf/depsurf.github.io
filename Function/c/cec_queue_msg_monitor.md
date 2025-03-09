# Function: <code>cec_queue_msg_monitor</code>

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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587250768,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:268",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250768,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587518608,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518608,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587721600,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721600,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500898600,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500898600,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233417256,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233417256,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294354192,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294354192,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277677624,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277677624,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587362544,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587362544,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130768,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130768,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587677744,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587677744,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
```

```json
{
  "name": "cec_queue_msg_monitor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587784128,
      "name": "cec_queue_msg_monitor",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:281",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/media/cec/cec-adap.c:cec_data_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587784128,
      "name": "cec_queue_msg_monitor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
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
void cec_queue_msg_monitor(struct cec_adapter * adap, const struct cec_msg * msg, bool valid_la)
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
