# Struct: <code>fwnode_operations</code>

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
struct fwnode_operations {
    void (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(struct fwnode_handle *) device_is_available;
    bool (*)(struct fwnode_handle *, const char *) property_present;
    int (*)(struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(struct fwnode_handle *, const char *) get_named_child_node;
    struct fwnode_handle * (*)(struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    int (*)(const struct fwnode_handle *, struct device *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    int (*)(struct fwnode_handle *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    int (*)(struct fwnode_handle *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    int (*)(struct fwnode_handle *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *) device_dma_supported;
    enum dev_dma_attr (*)(const struct fwnode_handle *) device_get_dma_attr;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    void * (*)(struct fwnode_handle *, int) iomap;
    int (*)(const struct fwnode_handle *, unsigned int) irq_get;
    int (*)(struct fwnode_handle *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *) device_dma_supported;
    enum dev_dma_attr (*)(const struct fwnode_handle *) device_get_dma_attr;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    void * (*)(struct fwnode_handle *, int) iomap;
    int (*)(const struct fwnode_handle *, unsigned int) irq_get;
    int (*)(struct fwnode_handle *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *) device_dma_supported;
    enum dev_dma_attr (*)(const struct fwnode_handle *) device_get_dma_attr;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    void * (*)(struct fwnode_handle *, int) iomap;
    int (*)(const struct fwnode_handle *, unsigned int) irq_get;
    int (*)(struct fwnode_handle *) add_links;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *) device_dma_supported;
    enum dev_dma_attr (*)(const struct fwnode_handle *) device_get_dma_attr;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    const char * (*)(const struct fwnode_handle *) get_name;
    const char * (*)(const struct fwnode_handle *) get_name_prefix;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
    void * (*)(struct fwnode_handle *, int) iomap;
    int (*)(const struct fwnode_handle *, unsigned int) irq_get;
    int (*)(struct fwnode_handle *) add_links;
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
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
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
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fwnode_operations {
    struct fwnode_handle * (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(const struct fwnode_handle *) device_is_available;
    const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data;
    bool (*)(const struct fwnode_handle *, const char *) property_present;
    int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node;
    int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args;
    struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
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
struct fwnode_operations {
    void (*)(struct fwnode_handle *) get;
    void (*)(struct fwnode_handle *) put;
    bool (*)(struct fwnode_handle *) device_is_available;
    bool (*)(struct fwnode_handle *, const char *) property_present;
    int (*)(struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array;
    int (*)(struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array;
    struct fwnode_handle * (*)(struct fwnode_handle *) get_parent;
    struct fwnode_handle * (*)(struct fwnode_handle *, struct fwnode_handle *) get_next_child_node;
    struct fwnode_handle * (*)(struct fwnode_handle *, const char *) get_named_child_node;
    struct fwnode_handle * (*)(struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_remote_endpoint;
    struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_port_parent;
    int (*)(struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(const struct fwnode_handle *, const char *, const char *, unsigned int, unsigned int, struct fwnode_reference_args *) get_reference_args</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct fwnode_handle *) get</code> ➡️ <code>struct fwnode_handle * (*)(struct fwnode_handle *) get</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct fwnode_handle *) device_is_available</code> ➡️ <code>bool (*)(const struct fwnode_handle *) device_is_available</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct fwnode_handle *, const char *) property_present</code> ➡️ <code>bool (*)(const struct fwnode_handle *, const char *) property_present</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array</code> ➡️ <code>int (*)(const struct fwnode_handle *, const char *, unsigned int, void *, size_t) property_read_int_array</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array</code> ➡️ <code>int (*)(const struct fwnode_handle *, const char *, const char * *, size_t) property_read_string_array</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fwnode_handle * (*)(struct fwnode_handle *) get_parent</code> ➡️ <code>struct fwnode_handle * (*)(const struct fwnode_handle *) get_parent</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fwnode_handle * (*)(struct fwnode_handle *, struct fwnode_handle *) get_next_child_node</code> ➡️ <code>struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) get_next_child_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fwnode_handle * (*)(struct fwnode_handle *, const char *) get_named_child_node</code> ➡️ <code>struct fwnode_handle * (*)(const struct fwnode_handle *, const char *) get_named_child_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fwnode_handle * (*)(struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint</code> ➡️ <code>struct fwnode_handle * (*)(const struct fwnode_handle *, struct fwnode_handle *) graph_get_next_endpoint</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fwnode_handle * (*)(struct fwnode_handle *) graph_get_remote_endpoint</code> ➡️ <code>struct fwnode_handle * (*)(const struct fwnode_handle *) graph_get_remote_endpoint</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint</code> ➡️ <code>int (*)(const struct fwnode_handle *, struct fwnode_endpoint *) graph_parse_endpoint</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const void * (*)(const struct fwnode_handle *, const struct device *) device_get_match_data</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * (*)(const struct fwnode_handle *) get_name</code>
</li>
<li>
<b>Field added. </b>
<code>const char * (*)(const struct fwnode_handle *) get_name_prefix</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct fwnode_handle *, struct device *) add_links</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct fwnode_handle *, struct device *) add_links</code> ➡️ <code>int (*)(struct fwnode_handle *) add_links</code>
</li>
</ul>
</details>
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
<code>bool (*)(const struct fwnode_handle *) device_dma_supported</code>
</li>
<li>
<b>Field added. </b>
<code>enum dev_dma_attr (*)(const struct fwnode_handle *) device_get_dma_attr</code>
</li>
<li>
<b>Field added. </b>
<code>void * (*)(struct fwnode_handle *, int) iomap</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(const struct fwnode_handle *, unsigned int) irq_get</code>
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
