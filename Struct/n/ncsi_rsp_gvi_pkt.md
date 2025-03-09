# Struct: <code>ncsi_rsp_gvi_pkt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    unsigned char major;
    unsigned char minor;
    unsigned char update;
    unsigned char alpha1;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
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
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct ncsi_rsp_gvi_pkt {
    struct ncsi_rsp_pkt_hdr rsp;
    __be32 ncsi_version;
    unsigned char[3] reserved;
    unsigned char alpha2;
    unsigned char[12] fw_name;
    __be32 fw_version;
    __be16[4] pci_ids;
    __be32 mf_id;
    __be32 checksum;
}
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned char major</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char minor</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char update</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char alpha1</code>
</li>
<li>
<b>Field removed. </b>
<code>__be32 ncsi_version</code>
</li>
</ul>
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
