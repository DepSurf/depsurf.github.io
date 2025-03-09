# Struct: <code>page_req_dsc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 srr;
    u64 bof;
    u64 pasid_present;
    u64 lpig;
    u64 pasid;
    u64 bus;
    u64 private;
    u64 prg_index;
    u64 rd_req;
    u64 wr_req;
    u64 exe_req;
    u64 priv_req;
    u64 devfn;
    u64 addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 type</code>
</li>
<li>
<b>Field added. </b>
<code>u64 priv_data_present</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rsvd</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rid</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pm_req</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rsvd2</code>
</li>
<li>
<b>Field added. </b>
<code>u64 qw_0</code>
</li>
<li>
<b>Field added. </b>
<code>u64 qw_1</code>
</li>
<li>
<b>Field added. </b>
<code>u64[2] priv_data</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 srr</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 bof</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 bus</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 private</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 priv_req</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 devfn</code>
</li>
</ul>
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct page_req_dsc {
    u64 type;
    u64 pasid_present;
    u64 priv_data_present;
    u64 rsvd;
    u64 rid;
    u64 pasid;
    u64 exe_req;
    u64 pm_req;
    u64 rsvd2;
    u64 qw_0;
    u64 rd_req;
    u64 wr_req;
    u64 lpig;
    u64 prg_index;
    u64 addr;
    u64 qw_1;
    u64[2] priv_data;
}
```
</details>
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
