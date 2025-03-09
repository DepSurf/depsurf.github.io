# Function: <code>subflow_check_data_avail</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591097600,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:745",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591097600,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591174672,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:894",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591174672,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591111728,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:992",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591111728,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:1105",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591956928,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1271
    },
    {
      "addr": 18446744071592753855,
      "name": "subflow_check_data_avail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:1189",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593683936,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1382
    },
    {
      "addr": 18446744071594640837,
      "name": "subflow_check_data_avail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:1261",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595615088,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
    },
    {
      "addr": 18446744071596370049,
      "name": "subflow_check_data_avail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:1232",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596123200,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1394
    },
    {
      "addr": 18446744071596899327,
      "name": "subflow_check_data_avail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
bool subflow_check_data_avail(struct sock * ssk)
```

```json
{
  "name": "subflow_check_data_avail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "subflow_check_data_avail",
      "external": false,
      "loc": "net/mptcp/subflow.c:1257",
      "file": "net/mptcp/subflow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/subflow.c:mptcp_subflow_data_available",
        "net/mptcp/subflow.c:mptcp_subflow_data_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596996768,
      "name": "subflow_check_data_avail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1404
    },
    {
      "addr": 18446744071597824717,
      "name": "subflow_check_data_avail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool subflow_check_data_avail(struct sock * ssk)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
