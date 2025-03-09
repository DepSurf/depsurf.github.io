# Struct: <code>rio_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
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
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
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
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rio_dev {
    struct list_head global_list;
    struct list_head net_list;
    struct rio_net * net;
    bool do_enum;
    u16 did;
    u16 vid;
    u32 device_rev;
    u16 asm_did;
    u16 asm_vid;
    u16 asm_rev;
    u16 efptr;
    u32 pef;
    u32 swpinfo;
    u32 src_ops;
    u32 dst_ops;
    u32 comp_tag;
    u32 phys_efptr;
    u32 phys_rmap;
    u32 em_efptr;
    u64 dma_mask;
    struct rio_driver * driver;
    struct device dev;
    struct resource[16] riores;
    int (*)(struct rio_dev *, union rio_pw_msg *, int) pwcback;
    u16 destid;
    u8 hopcount;
    struct rio_dev * prev;
    atomic_t state;
    struct rio_switch[0] rswitch;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 phys_rmap</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t state</code>
</li>
</ul>
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
