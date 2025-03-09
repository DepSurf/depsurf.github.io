# Function: <code>qcom_scm_call</code>

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
int qcom_scm_call(struct device * dev, u32 svc_id, u32 cmd_id, const struct qcom_scm_desc * desc, struct arm_smccc_res * res)
```

```json
{
  "name": "qcom_scm_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501491632,
      "name": "qcom_scm_call",
      "external": false,
      "loc": "drivers/firmware/qcom_scm-64.c:75",
      "file": "drivers/firmware/qcom_scm-64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_io_writel",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_io_readl",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_set_dload_mode",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_iommu_secure_ptbl_init",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_iommu_secure_ptbl_size",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_restore_sec_cfg",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_assign_mem",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_set_remote_state",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_mss_reset",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_shutdown",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_auth_and_reset",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_mem_setup",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_init_image",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_pas_supported",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_hdcp_req",
        "drivers/firmware/qcom_scm-64.c:__qcom_scm_is_call_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501491632,
      "name": "qcom_scm_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
int qcom_scm_call(struct device * dev, u32 svc_id, u32 cmd_id, const void * cmd_buf, size_t cmd_len, void * resp_buf, size_t resp_len)
```

```json
{
  "name": "qcom_scm_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234029940,
      "name": "qcom_scm_call",
      "external": false,
      "loc": "drivers/firmware/qcom_scm-32.c:162",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_set_remote_state",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_mss_reset",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_shutdown",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_auth_and_reset",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_mem_setup",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_init_image",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_pas_supported",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_hdcp_req",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_is_call_available",
        "drivers/firmware/qcom_scm-32.c:__qcom_scm_set_warm_boot_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234029940,
      "name": "qcom_scm_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
int qcom_scm_call(struct device * dev, u32 svc_id, u32 cmd_id, const struct qcom_scm_desc * desc, struct arm_smccc_res * res)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int qcom_scm_call(struct device * dev, u32 svc_id, u32 cmd_id, const void * cmd_buf, size_t cmd_len, void * resp_buf, size_t resp_len)
```
</details>
</li>
</ul>
