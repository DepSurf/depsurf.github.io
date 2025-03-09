# Struct: <code>tty_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    int alt_speed;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    int alt_speed;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    int alt_speed;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    struct (anon) flow;
    struct (anon) ctrl;
    int hw_stopped;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    struct (anon) flow;
    struct (anon) ctrl;
    int hw_stopped;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    struct (anon) flow;
    struct (anon) ctrl;
    int hw_stopped;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    struct (anon) flow;
    struct (anon) ctrl;
    bool hw_stopped;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tty_struct {
    struct kref kref;
    int index;
    struct device * dev;
    struct tty_driver * driver;
    struct tty_port * port;
    const struct tty_operations * ops;
    struct tty_ldisc * ldisc;
    struct ld_semaphore ldisc_sem;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    struct ktermios termios;
    struct ktermios termios_locked;
    char[64] name;
    long unsigned int flags;
    int count;
    unsigned int receive_room;
    struct winsize winsize;
    struct (anon) flow;
    struct (anon) ctrl;
    bool hw_stopped;
    bool closing;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    int write_cnt;
    u8 * write_buf;
    struct list_head tty_files;
    struct work_struct SAK_work;
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
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
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
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tty_struct {
    int magic;
    struct kref kref;
    struct device * dev;
    struct tty_driver * driver;
    const struct tty_operations * ops;
    int index;
    struct ld_semaphore ldisc_sem;
    struct tty_ldisc * ldisc;
    struct mutex atomic_write_lock;
    struct mutex legacy_mutex;
    struct mutex throttle_mutex;
    struct rw_semaphore termios_rwsem;
    struct mutex winsize_mutex;
    spinlock_t ctrl_lock;
    spinlock_t flow_lock;
    struct ktermios termios;
    struct ktermios termios_locked;
    struct termiox * termiox;
    char[64] name;
    struct pid * pgrp;
    struct pid * session;
    long unsigned int flags;
    int count;
    struct winsize winsize;
    long unsigned int stopped;
    long unsigned int flow_stopped;
    long unsigned int unused;
    int hw_stopped;
    long unsigned int ctrl_status;
    long unsigned int packet;
    long unsigned int unused_ctrl;
    unsigned int receive_room;
    int flow_change;
    struct tty_struct * link;
    struct fasync_struct * fasync;
    wait_queue_head_t write_wait;
    wait_queue_head_t read_wait;
    struct work_struct hangup_work;
    void * disc_data;
    void * driver_data;
    spinlock_t files_lock;
    struct list_head tty_files;
    int closing;
    unsigned char * write_buf;
    int write_cnt;
    struct work_struct SAK_work;
    struct tty_port * port;
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
<code>spinlock_t files_lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int alt_speed</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct termiox * termiox</code>
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
<code>struct (anon) flow</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) ctrl</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t ctrl_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t flow_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pid * pgrp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pid * session</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int stopped</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int flow_stopped</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int unused</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int ctrl_status</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int packet</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int unused_ctrl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int magic</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int hw_stopped</code> ➡️ <code>bool hw_stopped</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int closing</code> ➡️ <code>bool closing</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char * write_buf</code> ➡️ <code>u8 * write_buf</code>
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
