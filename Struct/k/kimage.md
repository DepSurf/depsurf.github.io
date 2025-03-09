# Struct: <code>kimage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
    void * elf_headers;
    long unsigned int elf_headers_sz;
    long unsigned int elf_load_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
    void * elf_headers;
    long unsigned int elf_headers_sz;
    long unsigned int elf_load_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
    void * elf_headers;
    long unsigned int elf_headers_sz;
    long unsigned int elf_load_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
    void * ima_buffer;
    phys_addr_t ima_buffer_addr;
    size_t ima_buffer_size;
    void * elf_headers;
    long unsigned int elf_headers_sz;
    long unsigned int elf_load_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
    void * ima_buffer;
    phys_addr_t ima_buffer_addr;
    size_t ima_buffer_size;
    void * elf_headers;
    long unsigned int elf_headers_sz;
    long unsigned int elf_load_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    unsigned int update_elfcorehdr;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
    int hp_action;
    int elfcorehdr_index;
    bool elfcorehdr_updated;
    void * ima_buffer;
    phys_addr_t ima_buffer_addr;
    size_t ima_buffer_size;
    void * elf_headers;
    long unsigned int elf_headers_sz;
    long unsigned int elf_load_addr;
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
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
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
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
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
<code>void * vmcoreinfo_data_copy</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct kexec_file_ops * fops</code> ➡️ <code>const struct kexec_file_ops * fops</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * elf_headers</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int elf_headers_sz</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int elf_load_addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * ima_buffer</code>
</li>
<li>
<b>Field added. </b>
<code>phys_addr_t ima_buffer_addr</code>
</li>
<li>
<b>Field added. </b>
<code>size_t ima_buffer_size</code>
</li>
</ul>
</details>
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
<code>unsigned int update_elfcorehdr</code>
</li>
<li>
<b>Field added. </b>
<code>int hp_action</code>
</li>
<li>
<b>Field added. </b>
<code>int elfcorehdr_index</code>
</li>
<li>
<b>Field added. </b>
<code>bool elfcorehdr_updated</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void * kernel_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int kernel_buf_len</code>
</li>
<li>
<b>Field removed. </b>
<code>void * initrd_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int initrd_buf_len</code>
</li>
<li>
<b>Field removed. </b>
<code>char * cmdline_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cmdline_buf_len</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct kexec_file_ops * fops</code>
</li>
<li>
<b>Field removed. </b>
<code>void * image_loader_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct purgatory_info purgatory_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct kimage {
    kimage_entry_t head;
    kimage_entry_t * entry;
    kimage_entry_t * last_entry;
    long unsigned int start;
    struct page * control_code_page;
    struct page * swap_page;
    void * vmcoreinfo_data_copy;
    long unsigned int nr_segments;
    struct kexec_segment[16] segment;
    struct list_head control_pages;
    struct list_head dest_pages;
    struct list_head unusable_pages;
    long unsigned int control_page;
    unsigned int type;
    unsigned int preserve_context;
    unsigned int file_mode;
    struct kimage_arch arch;
    void * kernel_buf;
    long unsigned int kernel_buf_len;
    void * initrd_buf;
    long unsigned int initrd_buf_len;
    char * cmdline_buf;
    long unsigned int cmdline_buf_len;
    const struct kexec_file_ops * fops;
    void * image_loader_data;
    struct purgatory_info purgatory_info;
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
