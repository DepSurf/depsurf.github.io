# Function: <code>ptp_convert_timestamp</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ktime_t ptp_convert_timestamp(const struct skb_shared_hwtstamps * hwtstamps, int vclock_index)
```

```json
{
  "name": "ptp_convert_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptp_convert_timestamp",
      "external": true,
      "loc": "drivers/ptp/ptp_vclock.c:188",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592632881,
      "name": "ptp_convert_timestamp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589179552,
      "name": "ptp_convert_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ktime_t ptp_convert_timestamp(const ktime_t * hwtstamp, int vclock_index)
```

```json
{
  "name": "ptp_convert_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590635952,
      "name": "ptp_convert_timestamp",
      "external": true,
      "loc": "drivers/ptp/ptp_vclock.c:268",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590635952,
      "name": "ptp_convert_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
ktime_t ptp_convert_timestamp(const ktime_t * hwtstamp, int vclock_index)
```

```json
{
  "name": "ptp_convert_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592299760,
      "name": "ptp_convert_timestamp",
      "external": true,
      "loc": "drivers/ptp/ptp_vclock.c:268",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592299760,
      "name": "ptp_convert_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ktime_t ptp_convert_timestamp(const ktime_t * hwtstamp, int vclock_index)
```

```json
{
  "name": "ptp_convert_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592724816,
      "name": "ptp_convert_timestamp",
      "external": true,
      "loc": "drivers/ptp/ptp_vclock.c:268",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592724816,
      "name": "ptp_convert_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
ktime_t ptp_convert_timestamp(const ktime_t * hwtstamp, int vclock_index)
```

```json
{
  "name": "ptp_convert_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593472656,
      "name": "ptp_convert_timestamp",
      "external": true,
      "loc": "drivers/ptp/ptp_vclock.c:268",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593472656,
      "name": "ptp_convert_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
ktime_t ptp_convert_timestamp(const struct skb_shared_hwtstamps * hwtstamps, int vclock_index)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ktime_t * hwtstamp</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct skb_shared_hwtstamps * hwtstamps</code>
</li>
</ul>
</details>
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
