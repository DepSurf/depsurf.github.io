# Struct: <code>pnp_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
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
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
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
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pnp_dev {
    struct device dev;
    u64 dma_mask;
    unsigned int number;
    int status;
    struct list_head global_list;
    struct list_head protocol_list;
    struct list_head card_list;
    struct list_head rdev_list;
    struct pnp_protocol * protocol;
    struct pnp_card * card;
    struct pnp_driver * driver;
    struct pnp_card_link * card_link;
    struct pnp_id * id;
    int active;
    int capabilities;
    unsigned int num_dependent_sets;
    struct list_head resources;
    struct list_head options;
    char[50] name;
    int flags;
    struct proc_dir_entry * procent;
    void * data;
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
