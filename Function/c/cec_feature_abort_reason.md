# Function: <code>cec_feature_abort_reason</code>

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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587255152,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1774",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587255152,
      "name": "cec_feature_abort_reason",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524240,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1835",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524240,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587727328,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727328,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500904824,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500904824,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233423404,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233423404,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294362256,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294362256,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277682812,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277682812,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368272,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368272,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136496,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136496,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587683472,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683472,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
```

```json
{
  "name": "cec_feature_abort_reason",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587789840,
      "name": "cec_feature_abort_reason",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1852",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789840,
      "name": "cec_feature_abort_reason",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
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
int cec_feature_abort_reason(struct cec_adapter * adap, struct cec_msg * msg, u8 reason)
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
