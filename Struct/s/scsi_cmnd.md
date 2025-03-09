# Struct: <code>scsi_cmnd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int serial_number;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
    unsigned int extra_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
    unsigned int extra_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    int budget_token;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
    unsigned int extra_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    int budget_token;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned int extra_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    int budget_token;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    enum scsi_cmnd_submitter submitter;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    unsigned int resid_len;
    unsigned int sense_len;
    unsigned char * sense_buffer;
    int flags;
    long unsigned int state;
    unsigned int extra_len;
    unsigned char * host_scribble;
    int result;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    int budget_token;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    enum scsi_cmnd_submitter submitter;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    unsigned int resid_len;
    unsigned int sense_len;
    unsigned char * sense_buffer;
    int flags;
    long unsigned int state;
    unsigned int extra_len;
    unsigned char * host_scribble;
    int result;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    int budget_token;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    enum scsi_cmnd_submitter submitter;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    unsigned int resid_len;
    unsigned int sense_len;
    unsigned char * sense_buffer;
    int flags;
    long unsigned int state;
    unsigned int extra_len;
    unsigned char * host_scribble;
    int result;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_device * device;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    int budget_token;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    enum scsi_cmnd_submitter submitter;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char[32] cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    unsigned int resid_len;
    unsigned int sense_len;
    unsigned char * sense_buffer;
    int flags;
    long unsigned int state;
    unsigned int extra_len;
    unsigned char * host_scribble;
    int result;
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
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
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
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_cmnd {
    struct scsi_request req;
    struct scsi_device * device;
    struct list_head list;
    struct list_head eh_entry;
    struct delayed_work abort_work;
    struct callback_head rcu;
    int eh_eflags;
    long unsigned int jiffies_at_alloc;
    int retries;
    int allowed;
    unsigned char prot_op;
    unsigned char prot_type;
    unsigned char prot_flags;
    short unsigned int cmd_len;
    enum dma_data_direction sc_data_direction;
    unsigned char * cmnd;
    struct scsi_data_buffer sdb;
    struct scsi_data_buffer * prot_sdb;
    unsigned int underflow;
    unsigned int transfersize;
    struct request * request;
    unsigned char * sense_buffer;
    void (*)(struct scsi_cmnd *) scsi_done;
    struct scsi_pointer SCp;
    unsigned char * host_scribble;
    int result;
    int flags;
    long unsigned int state;
    unsigned char tag;
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
<code>struct scsi_request req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
</ul>
</details>
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
<code>long unsigned int state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int serial_number</code>
</li>
</ul>
</details>
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
<code>unsigned int extra_len</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
</ul>
</details>
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
<code>int budget_token</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct request * request</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char tag</code>
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
<code>enum scsi_cmnd_submitter submitter</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int resid_len</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sense_len</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scsi_request req</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct scsi_cmnd *) scsi_done</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scsi_pointer SCp</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char * cmnd</code> ➡️ <code>unsigned char[32] cmnd</code>
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
