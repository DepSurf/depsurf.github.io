# Struct: <code>ohci_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    struct dentry * debug_async;
    struct dentry * debug_periodic;
    struct dentry * debug_registers;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    struct dentry * debug_async;
    struct dentry * debug_periodic;
    struct dentry * debug_registers;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    struct dentry * debug_async;
    struct dentry * debug_periodic;
    struct dentry * debug_registers;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    struct dentry * debug_async;
    struct dentry * debug_periodic;
    struct dentry * debug_registers;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    struct dentry * debug_async;
    struct dentry * debug_periodic;
    struct dentry * debug_registers;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
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
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
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
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct dentry * debug_async</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dentry * debug_periodic</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dentry * debug_registers</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct ohci_hcd {
    spinlock_t lock;
    struct ohci_regs * regs;
    struct ohci_hcca * hcca;
    dma_addr_t hcca_dma;
    struct ed * ed_rm_list;
    struct ed * ed_bulktail;
    struct ed * ed_controltail;
    struct ed *[32] periodic;
    void (*)(struct ohci_hcd *) start_hnp;
    struct dma_pool * td_cache;
    struct dma_pool * ed_cache;
    struct td *[64] td_hash;
    struct td * dl_start;
    struct td * dl_end;
    struct list_head pending;
    struct list_head eds_in_use;
    enum ohci_rh_state rh_state;
    int num_ports;
    int[32] load;
    u32 hc_control;
    long unsigned int next_statechange;
    u32 fminterval;
    unsigned int autostop;
    unsigned int working;
    unsigned int restart_work;
    long unsigned int flags;
    unsigned int prev_frame_no;
    unsigned int wdh_cnt;
    unsigned int prev_wdh_cnt;
    u32 prev_donehead;
    struct timer_list io_watchdog;
    struct work_struct nec_work;
    struct dentry * debug_dir;
    long unsigned int[0] priv;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
