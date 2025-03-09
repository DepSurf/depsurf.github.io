# Function: <code>cmd_db_get_header</code>

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
int cmd_db_get_header(const char * id, const struct entry_header * * eh, const struct rsc_hdr * * rh)
```

```json
{
  "name": "cmd_db_get_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498130304,
      "name": "cmd_db_get_header",
      "external": false,
      "loc": "drivers/soc/qcom/cmd-db.c:136",
      "file": "drivers/soc/qcom/cmd-db.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/qcom/cmd-db.c:cmd_db_read_slave_id",
        "drivers/soc/qcom/cmd-db.c:cmd_db_read_aux_data",
        "drivers/soc/qcom/cmd-db.c:cmd_db_read_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498130304,
      "name": "cmd_db_get_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int cmd_db_get_header(const char * id, const struct entry_header * * eh, const struct rsc_hdr * * rh)
```

```json
{
  "name": "cmd_db_get_header",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230890828,
      "name": "cmd_db_get_header",
      "external": false,
      "loc": "drivers/soc/qcom/cmd-db.c:136",
      "file": "drivers/soc/qcom/cmd-db.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/qcom/cmd-db.c:cmd_db_read_slave_id",
        "drivers/soc/qcom/cmd-db.c:cmd_db_read_aux_data",
        "drivers/soc/qcom/cmd-db.c:cmd_db_read_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230890828,
      "name": "cmd_db_get_header",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int cmd_db_get_header(const char * id, const struct entry_header * * eh, const struct rsc_hdr * * rh)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cmd_db_get_header(const char * id, const struct entry_header * * eh, const struct rsc_hdr * * rh)
```
</details>
</li>
</ul>
