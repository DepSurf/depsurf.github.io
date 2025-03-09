# Function: <code>scmi_perf_domain_desc_fc</code>

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
void scmi_perf_domain_desc_fc(const struct scmi_handle * handle, u32 domain, u32 message_id, void * * p_addr, struct scmi_fc_db_info * * p_db)
```

```json
{
  "name": "scmi_perf_domain_desc_fc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501527704,
      "name": "scmi_perf_domain_desc_fc",
      "external": false,
      "loc": "drivers/firmware/arm_scmi/perf.c:495",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501527704,
      "name": "scmi_perf_domain_desc_fc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void scmi_perf_domain_desc_fc(const struct scmi_handle * handle, u32 domain, u32 message_id, void * * p_addr, struct scmi_fc_db_info * * p_db)
```

```json
{
  "name": "scmi_perf_domain_desc_fc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234044400,
      "name": "scmi_perf_domain_desc_fc",
      "external": false,
      "loc": "drivers/firmware/arm_scmi/perf.c:495",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234044400,
      "name": "scmi_perf_domain_desc_fc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void scmi_perf_domain_desc_fc(const struct scmi_handle * handle, u32 domain, u32 message_id, void * * p_addr, struct scmi_fc_db_info * * p_db)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void scmi_perf_domain_desc_fc(const struct scmi_handle * handle, u32 domain, u32 message_id, void * * p_addr, struct scmi_fc_db_info * * p_db)
```
</details>
</li>
</ul>
