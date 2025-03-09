# Function: <code>cec_fill_msg_report_features</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587259194,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587516816,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1807",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516816,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719792,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719792,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500896672,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500896672,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233415376,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233415376,
      "name": "cec_fill_msg_report_features",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294351712,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294351712,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277675908,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277675908,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587360736,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360736,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128960,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128960,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587675936,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587675936,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```

```json
{
  "name": "cec_fill_msg_report_features",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587782320,
      "name": "cec_fill_msg_report_features",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1824",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782320,
      "name": "cec_fill_msg_report_features",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void cec_fill_msg_report_features(struct cec_adapter * adap, struct cec_msg * msg, unsigned int la_idx)
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
