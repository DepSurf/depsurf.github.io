# Struct: <code>rio_mport</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head node;
    struct list_head nnode;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    enum rio_phy_type phy_type;
    u32 phys_efptr;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
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
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
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
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rio_mport {
    struct list_head dbells;
    struct list_head pwrites;
    struct list_head node;
    struct list_head nnode;
    struct rio_net * net;
    struct mutex lock;
    struct resource iores;
    struct resource[16] riores;
    struct rio_msg[4] inb_msg;
    struct rio_msg[4] outb_msg;
    int host_deviceid;
    struct rio_ops * ops;
    unsigned char id;
    unsigned char index;
    unsigned int sys_size;
    u32 phys_efptr;
    u32 phys_rmap;
    unsigned char[40] name;
    struct device dev;
    void * priv;
    struct dma_device dma;
    struct rio_scan * nscan;
    atomic_t state;
    unsigned int pwe_refcnt;
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
<code>struct list_head pwrites</code>
</li>
<li>
<b>Field added. </b>
<code>struct rio_net * net</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex lock</code>
</li>
<li>
<b>Field added. </b>
<code>u32 phys_rmap</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t state</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pwe_refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>enum rio_phy_type phy_type</code>
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
