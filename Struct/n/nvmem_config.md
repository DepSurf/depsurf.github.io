# Struct: <code>nvmem_config</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    bool read_only;
    bool root_only;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    bool read_only;
    bool root_only;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    bool read_only;
    bool root_only;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    struct gpio_desc * wp_gpio;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    struct gpio_desc * wp_gpio;
    const struct nvmem_cell_info * cells;
    int ncells;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    struct gpio_desc * wp_gpio;
    const struct nvmem_cell_info * cells;
    int ncells;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    struct gpio_desc * wp_gpio;
    const struct nvmem_cell_info * cells;
    int ncells;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool ignore_wp;
    struct device_node * of_node;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    struct gpio_desc * wp_gpio;
    const struct nvmem_cell_info * cells;
    int ncells;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool ignore_wp;
    struct device_node * of_node;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    nvmem_cell_post_process_t cell_post_process;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool ignore_wp;
    struct device_node * of_node;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    nvmem_cell_post_process_t cell_post_process;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool ignore_wp;
    struct nvmem_layout * layout;
    struct device_node * of_node;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    bool add_legacy_fixed_of_cells;
    void (*)(struct nvmem_device *, struct nvmem_cell_info *) fixup_dt_cell_info;
    const struct nvmem_keepout * keepout;
    unsigned int nkeepout;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool ignore_wp;
    struct nvmem_layout * layout;
    struct device_node * of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
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
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
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
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    enum nvmem_type type;
    bool read_only;
    bool root_only;
    bool no_of_node;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct nvmem_config {
    struct device * dev;
    const char * name;
    int id;
    struct module * owner;
    const struct nvmem_cell_info * cells;
    int ncells;
    bool read_only;
    bool root_only;
    nvmem_reg_read_t reg_read;
    nvmem_reg_write_t reg_write;
    int size;
    int word_size;
    int stride;
    void * priv;
    bool compat;
    struct device * base_dev;
}
```
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
<code>enum nvmem_type type</code>
</li>
<li>
<b>Field added. </b>
<code>bool no_of_node</code>
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
<b>Field added. </b>
<code>struct gpio_desc * wp_gpio</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct nvmem_keepout * keepout</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int nkeepout</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool ignore_wp</code>
</li>
<li>
<b>Field added. </b>
<code>struct device_node * of_node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>nvmem_cell_post_process_t cell_post_process</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct gpio_desc * wp_gpio</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct nvmem_layout * layout</code>
</li>
<li>
<b>Field removed. </b>
<code>nvmem_cell_post_process_t cell_post_process</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool add_legacy_fixed_of_cells</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct nvmem_device *, struct nvmem_cell_info *) fixup_dt_cell_info</code>
</li>
<li>
<b>Field removed. </b>
<code>bool no_of_node</code>
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
