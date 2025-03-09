# Struct: <code>usb_cdc_parsed_header</code>

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
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
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
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
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
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
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
struct usb_cdc_parsed_header {
    struct usb_cdc_union_desc * usb_cdc_union_desc;
    struct usb_cdc_header_desc * usb_cdc_header_desc;
    struct usb_cdc_call_mgmt_descriptor * usb_cdc_call_mgmt_descriptor;
    struct usb_cdc_acm_descriptor * usb_cdc_acm_descriptor;
    struct usb_cdc_country_functional_desc * usb_cdc_country_functional_desc;
    struct usb_cdc_network_terminal_desc * usb_cdc_network_terminal_desc;
    struct usb_cdc_ether_desc * usb_cdc_ether_desc;
    struct usb_cdc_dmm_desc * usb_cdc_dmm_desc;
    struct usb_cdc_mdlm_desc * usb_cdc_mdlm_desc;
    struct usb_cdc_mdlm_detail_desc * usb_cdc_mdlm_detail_desc;
    struct usb_cdc_obex_desc * usb_cdc_obex_desc;
    struct usb_cdc_ncm_desc * usb_cdc_ncm_desc;
    struct usb_cdc_mbim_desc * usb_cdc_mbim_desc;
    struct usb_cdc_mbim_extended_desc * usb_cdc_mbim_extended_desc;
    bool phonet_magic_present;
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
