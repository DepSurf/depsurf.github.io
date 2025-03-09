# Function: <code>get_mapping_status</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:617",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591096560,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1031
    },
    {
      "addr": 18446744071591101225,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:739",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173392,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1272
    },
    {
      "addr": 18446744071591640832,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591110256,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:830",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591110256,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:927",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591955248,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
    },
    {
      "addr": 18446744071592753806,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:970",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593682304,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1397
    },
    {
      "addr": 18446744071594640787,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:1042",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595613360,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1460
    },
    {
      "addr": 18446744071596369999,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:1018",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596121744,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1429
    },
    {
      "addr": 18446744071596899277,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk, struct mptcp_sock * msk)
```

```json
{
  "name": "get_mapping_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mapping_status",
      "external": false,
      "loc": "net/mptcp/subflow.c:1043",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596995312,
      "name": "get_mapping_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1429
    },
    {
      "addr": 18446744071597824667,
      "name": "get_mapping_status.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
enum mapping_status get_mapping_status(struct sock * ssk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mptcp_sock * msk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
