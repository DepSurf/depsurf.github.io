# Struct: <code>drm_device</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct drm_device {
    int if_version;
    struct kref ref;
    struct device * dev;
    struct (anon) managed;
    const struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    struct drm_minor * accel;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    atomic_t open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
    struct dentry * debugfs_root;
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
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
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
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct drm_device {
    struct list_head legacy_dev_list;
    int if_version;
    struct kref ref;
    struct device * dev;
    struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    int open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool irq_enabled;
    int irq;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    struct drm_agp_head * agp;
    struct pci_dev * pdev;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct drm_device {
    int if_version;
    struct kref ref;
    struct device * dev;
    struct (anon) managed;
    const struct drm_driver * driver;
    void * dev_private;
    struct drm_minor * primary;
    struct drm_minor * render;
    struct drm_minor * accel;
    bool registered;
    struct drm_master * master;
    u32 driver_features;
    bool unplugged;
    struct inode * anon_inode;
    char * unique;
    struct mutex struct_mutex;
    struct mutex master_mutex;
    atomic_t open_count;
    struct mutex filelist_mutex;
    struct list_head filelist;
    struct list_head filelist_internal;
    struct mutex clientlist_mutex;
    struct list_head clientlist;
    bool vblank_disable_immediate;
    struct drm_vblank_crtc * vblank;
    spinlock_t vblank_time_lock;
    spinlock_t vbl_lock;
    u32 max_vblank_count;
    struct list_head vblank_event_list;
    spinlock_t event_lock;
    unsigned int num_crtcs;
    struct drm_mode_config mode_config;
    struct mutex object_name_lock;
    struct idr object_name_idr;
    struct drm_vma_offset_manager * vma_offset_manager;
    struct drm_vram_mm * vram_mm;
    enum switch_power_state switch_power_state;
    struct drm_fb_helper * fb_helper;
    struct dentry * debugfs_root;
}
```
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
