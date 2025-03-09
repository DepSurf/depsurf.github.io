# Function: <code>scmi_perf_level_set</code>

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
int scmi_perf_level_set(const struct scmi_handle * handle, u32 domain, u32 level, bool poll)
```

```json
{
  "name": "scmi_perf_level_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501527080,
      "name": "scmi_perf_level_set",
      "external": false,
      "loc": "drivers/firmware/arm_scmi/perf.c:434",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_scmi/perf.c:scmi_dvfs_freq_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501527080,
      "name": "scmi_perf_level_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int scmi_perf_level_set(const struct scmi_handle * handle, u32 domain, u32 level, bool poll)
```

```json
{
  "name": "scmi_perf_level_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234043768,
      "name": "scmi_perf_level_set",
      "external": false,
      "loc": "drivers/firmware/arm_scmi/perf.c:434",
      "file": "drivers/firmware/arm_scmi/perf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_scmi/perf.c:scmi_dvfs_freq_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234043768,
      "name": "scmi_perf_level_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int scmi_perf_level_set(const struct scmi_handle * handle, u32 domain, u32 level, bool poll)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int scmi_perf_level_set(const struct scmi_handle * handle, u32 domain, u32 level, bool poll)
```
</details>
</li>
</ul>
