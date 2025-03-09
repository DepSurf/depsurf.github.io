# Struct: <code>boot_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u8[16] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct e820entry[128] e820_map;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u8[16] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct e820entry[128] e820_map;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u8[16] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct e820entry[128] e820_map;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u8[16] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u8[16] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u8[16] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[112] _pad4;
    __u32 cc_blob_address;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[112] _pad4;
    __u32 cc_blob_address;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[112] _pad4;
    __u32 cc_blob_address;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[112] _pad4;
    __u32 cc_blob_address;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[36] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
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
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct boot_e820_entry[128] e820_table</code>
</li>
<li>
<b>Field removed. </b>
<code>struct e820entry[128] e820_map</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 acpi_rsdp_addr</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[16] _pad3</code> ➡️ <code>__u8[8] _pad3</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u8[40] _pad7</code> ➡️ <code>__u8[36] _pad7</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 cc_blob_address</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u8[116] _pad4</code> ➡️ <code>__u8[112] _pad4</code>
</li>
</ul>
</details>
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
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct boot_params {
    struct screen_info screen_info;
    struct apm_bios_info apm_bios_info;
    __u8[4] _pad2;
    __u64 tboot_addr;
    struct ist_info ist_info;
    __u64 acpi_rsdp_addr;
    __u8[8] _pad3;
    __u8[16] hd0_info;
    __u8[16] hd1_info;
    struct sys_desc_table sys_desc_table;
    struct olpc_ofw_header olpc_ofw_header;
    __u32 ext_ramdisk_image;
    __u32 ext_ramdisk_size;
    __u32 ext_cmd_line_ptr;
    __u8[116] _pad4;
    struct edid_info edid_info;
    struct efi_info efi_info;
    __u32 alt_mem_k;
    __u32 scratch;
    __u8 e820_entries;
    __u8 eddbuf_entries;
    __u8 edd_mbr_sig_buf_entries;
    __u8 kbd_status;
    __u8 secure_boot;
    __u8[2] _pad5;
    __u8 sentinel;
    __u8[1] _pad6;
    struct setup_header hdr;
    __u8[40] _pad7;
    __u32[16] edd_mbr_sig_buffer;
    struct boot_e820_entry[128] e820_table;
    __u8[48] _pad8;
    struct edd_info[6] eddbuf;
    __u8[276] _pad9;
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
