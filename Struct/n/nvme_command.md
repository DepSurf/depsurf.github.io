# Struct: <code>nvme_command</code>

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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct nvme_command {
    struct nvme_common_command common;
    struct nvme_rw_command rw;
    struct nvme_identify identify;
    struct nvme_features features;
    struct nvme_create_cq create_cq;
    struct nvme_create_sq create_sq;
    struct nvme_delete_queue delete_queue;
    struct nvme_download_firmware dlfw;
    struct nvme_format_cmd format;
    struct nvme_dsm_cmd dsm;
    struct nvme_write_zeroes_cmd write_zeroes;
    struct nvme_abort_cmd abort;
    struct nvme_get_log_page_command get_log_page;
    struct nvmf_common_command fabrics;
    struct nvmf_connect_command connect;
    struct nvmf_property_set_command prop_set;
    struct nvmf_property_get_command prop_get;
    struct nvme_dbbuf dbbuf;
    struct nvme_directive_cmd directive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvme_command {
    struct nvme_common_command common;
    struct nvme_rw_command rw;
    struct nvme_identify identify;
    struct nvme_features features;
    struct nvme_create_cq create_cq;
    struct nvme_create_sq create_sq;
    struct nvme_delete_queue delete_queue;
    struct nvme_download_firmware dlfw;
    struct nvme_format_cmd format;
    struct nvme_dsm_cmd dsm;
    struct nvme_write_zeroes_cmd write_zeroes;
    struct nvme_abort_cmd abort;
    struct nvme_get_log_page_command get_log_page;
    struct nvmf_common_command fabrics;
    struct nvmf_connect_command connect;
    struct nvmf_property_set_command prop_set;
    struct nvmf_property_get_command prop_get;
    struct nvme_dbbuf dbbuf;
    struct nvme_directive_cmd directive;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
struct nvme_command {
    struct nvme_common_command common;
    struct nvme_rw_command rw;
    struct nvme_identify identify;
    struct nvme_features features;
    struct nvme_create_cq create_cq;
    struct nvme_create_sq create_sq;
    struct nvme_delete_queue delete_queue;
    struct nvme_download_firmware dlfw;
    struct nvme_format_cmd format;
    struct nvme_dsm_cmd dsm;
    struct nvme_write_zeroes_cmd write_zeroes;
    struct nvme_abort_cmd abort;
    struct nvme_get_log_page_command get_log_page;
    struct nvmf_common_command fabrics;
    struct nvmf_connect_command connect;
    struct nvmf_property_set_command prop_set;
    struct nvmf_property_get_command prop_get;
    struct nvme_dbbuf dbbuf;
    struct nvme_directive_cmd directive;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct nvme_command {
    struct nvme_common_command common;
    struct nvme_rw_command rw;
    struct nvme_identify identify;
    struct nvme_features features;
    struct nvme_create_cq create_cq;
    struct nvme_create_sq create_sq;
    struct nvme_delete_queue delete_queue;
    struct nvme_download_firmware dlfw;
    struct nvme_format_cmd format;
    struct nvme_dsm_cmd dsm;
    struct nvme_write_zeroes_cmd write_zeroes;
    struct nvme_abort_cmd abort;
    struct nvme_get_log_page_command get_log_page;
    struct nvmf_common_command fabrics;
    struct nvmf_connect_command connect;
    struct nvmf_property_set_command prop_set;
    struct nvmf_property_get_command prop_get;
    struct nvme_dbbuf dbbuf;
    struct nvme_directive_cmd directive;
}
```
</details>
</li>
</ul>
