# Function: <code>cec_transmit_done_ts</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:564",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262411,
      "name": "cec_transmit_done_ts.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587251408,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:577",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530757,
      "name": "cec_transmit_done_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071587519264,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587733663,
      "name": "cec_transmit_done_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071587722304,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500899352,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500899352,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233417984,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233417984,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294355280,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294355280,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277678254,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277678254,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374607,
      "name": "cec_transmit_done_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071587363248,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587142831,
      "name": "cec_transmit_done_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071587131472,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689807,
      "name": "cec_transmit_done_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071587678448,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
```

```json
{
  "name": "cec_transmit_done_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_done_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts",
        "drivers/media/cec/cec-adap.c:cec_transmit_attempt_done_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587796175,
      "name": "cec_transmit_done_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071587784832,
      "name": "cec_transmit_done_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
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
void cec_transmit_done_ts(struct cec_adapter * adap, u8 status, u8 arb_lost_cnt, u8 nack_cnt, u8 low_drive_cnt, u8 error_cnt, ktime_t ts)
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
