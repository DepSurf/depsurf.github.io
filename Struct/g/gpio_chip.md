# Struct: <code>gpio_chip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct device * dev;
    struct device * cdev;
    struct module * owner;
    struct list_head list;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, unsigned int) set_debounce;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int base;
    u16 ngpio;
    struct gpio_desc * desc;
    const const char * * names;
    bool can_sleep;
    bool irq_not_threaded;
    struct irq_chip * irqchip;
    struct irq_domain * irqdomain;
    unsigned int irq_base;
    irq_flow_handler_t irq_handler;
    unsigned int irq_default_type;
    int irq_parent;
    struct lock_class_key * lock_key;
    struct list_head pin_ranges;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, unsigned int) set_debounce;
    int (*)(struct gpio_chip *, unsigned int, enum single_ended_mode) set_single_ended;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    bool irq_not_threaded;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    long unsigned int (*)(struct gpio_chip *, unsigned int) pin2mask;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct irq_chip * irqchip;
    struct irq_domain * irqdomain;
    unsigned int irq_base;
    irq_flow_handler_t irq_handler;
    unsigned int irq_default_type;
    int irq_parent;
    struct lock_class_key * lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, unsigned int) set_debounce;
    int (*)(struct gpio_chip *, unsigned int, enum single_ended_mode) set_single_ended;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    long unsigned int (*)(struct gpio_chip *, unsigned int) pin2mask;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct irq_chip * irqchip;
    struct irq_domain * irqdomain;
    unsigned int irq_base;
    irq_flow_handler_t irq_handler;
    unsigned int irq_default_type;
    int irq_chained_parent;
    bool irq_nested;
    bool irq_need_valid_mask;
    long unsigned int * irq_valid_mask;
    struct lock_class_key * lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    long unsigned int (*)(struct gpio_chip *, unsigned int) pin2mask;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct irq_chip * irqchip;
    struct irq_domain * irqdomain;
    unsigned int irq_base;
    irq_flow_handler_t irq_handler;
    unsigned int irq_default_type;
    unsigned int irq_chained_parent;
    bool irq_nested;
    bool irq_need_valid_mask;
    long unsigned int * irq_valid_mask;
    struct lock_class_key * lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    bool need_valid_mask;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir;
    bool bgpio_dir_inverted;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    bool need_valid_mask;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    bool need_valid_mask;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int base;
    u16 ngpio;
    u16 offset;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct fwnode_handle * fwnode;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int (*)(struct gpio_chip *, u32, long unsigned int) en_hw_timestamp;
    int (*)(struct gpio_chip *, u32, long unsigned int) dis_hw_timestamp;
    int base;
    u16 ngpio;
    u16 offset;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    raw_spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct fwnode_handle * fwnode;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int (*)(struct gpio_chip *, u32, long unsigned int) en_hw_timestamp;
    int (*)(struct gpio_chip *, u32, long unsigned int) dis_hw_timestamp;
    int base;
    u16 ngpio;
    u16 offset;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    raw_spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct fwnode_handle * fwnode;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int (*)(struct gpio_chip *, u32, long unsigned int) en_hw_timestamp;
    int (*)(struct gpio_chip *, u32, long unsigned int) dis_hw_timestamp;
    int base;
    u16 ngpio;
    u16 offset;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    raw_spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct fwnode_handle * fwnode;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int (*)(struct gpio_chip *) add_pin_ranges;
    int (*)(struct gpio_chip *, u32, long unsigned int) en_hw_timestamp;
    int (*)(struct gpio_chip *, u32, long unsigned int) dis_hw_timestamp;
    int base;
    u16 ngpio;
    u16 offset;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    raw_spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
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
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
    struct device_node * of_node;
    unsigned int of_gpio_n_cells;
    int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
    struct device_node * of_node;
    unsigned int of_gpio_n_cells;
    int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
    struct device_node * of_node;
    unsigned int of_gpio_n_cells;
    int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
    struct device_node * of_node;
    unsigned int of_gpio_n_cells;
    int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate;
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
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct gpio_chip {
    const char * label;
    struct gpio_device * gpiodev;
    struct device * parent;
    struct module * owner;
    int (*)(struct gpio_chip *, unsigned int) request;
    void (*)(struct gpio_chip *, unsigned int) free;
    int (*)(struct gpio_chip *, unsigned int) get_direction;
    int (*)(struct gpio_chip *, unsigned int) direction_input;
    int (*)(struct gpio_chip *, unsigned int, int) direction_output;
    int (*)(struct gpio_chip *, unsigned int) get;
    int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple;
    void (*)(struct gpio_chip *, unsigned int, int) set;
    void (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) set_multiple;
    int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config;
    int (*)(struct gpio_chip *, unsigned int) to_irq;
    void (*)(struct seq_file *, struct gpio_chip *) dbg_show;
    int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask;
    int base;
    u16 ngpio;
    const const char * * names;
    bool can_sleep;
    long unsigned int (*)(void *) read_reg;
    void (*)(void *, long unsigned int) write_reg;
    bool be_bits;
    void * reg_dat;
    void * reg_set;
    void * reg_clr;
    void * reg_dir_out;
    void * reg_dir_in;
    bool bgpio_dir_unreadable;
    int bgpio_bits;
    spinlock_t bgpio_lock;
    long unsigned int bgpio_data;
    long unsigned int bgpio_dir;
    struct gpio_irq_chip irq;
    long unsigned int * valid_mask;
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
<code>struct gpio_device * gpiodev</code>
</li>
<li>
<b>Field added. </b>
<code>struct device * parent</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, unsigned int, enum single_ended_mode) set_single_ended</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(void *) read_reg</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *, long unsigned int) write_reg</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct gpio_chip *, unsigned int) pin2mask</code>
</li>
<li>
<b>Field added. </b>
<code>void * reg_dat</code>
</li>
<li>
<b>Field added. </b>
<code>void * reg_set</code>
</li>
<li>
<b>Field added. </b>
<code>void * reg_clr</code>
</li>
<li>
<b>Field added. </b>
<code>void * reg_dir</code>
</li>
<li>
<b>Field added. </b>
<code>int bgpio_bits</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t bgpio_lock</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int bgpio_data</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int bgpio_dir</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device * cdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct gpio_desc * desc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head pin_ranges</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int irq_chained_parent</code>
</li>
<li>
<b>Field added. </b>
<code>bool irq_nested</code>
</li>
<li>
<b>Field added. </b>
<code>bool irq_need_valid_mask</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * irq_valid_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>bool irq_not_threaded</code>
</li>
<li>
<b>Field removed. </b>
<code>int irq_parent</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, unsigned int, long unsigned int) set_config</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct gpio_chip *, unsigned int, unsigned int) set_debounce</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct gpio_chip *, unsigned int, enum single_ended_mode) set_single_ended</code>
</li>
<li>
<b>Field type changed. </b>
<code>int irq_chained_parent</code> ➡️ <code>unsigned int irq_chained_parent</code>
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
<code>int (*)(struct gpio_chip *, long unsigned int *, long unsigned int *) get_multiple</code>
</li>
<li>
<b>Field added. </b>
<code>bool be_bits</code>
</li>
<li>
<b>Field added. </b>
<code>struct gpio_irq_chip irq</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)(struct gpio_chip *, unsigned int) pin2mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_chip * irqchip</code>
</li>
<li>
<b>Field removed. </b>
<code>struct irq_domain * irqdomain</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int irq_base</code>
</li>
<li>
<b>Field removed. </b>
<code>irq_flow_handler_t irq_handler</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int irq_default_type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int irq_chained_parent</code>
</li>
<li>
<b>Field removed. </b>
<code>bool irq_nested</code>
</li>
<li>
<b>Field removed. </b>
<code>bool irq_need_valid_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int * irq_valid_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key * lock_key</code>
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
<code>bool need_valid_mask</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * valid_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *) init_valid_mask</code>
</li>
<li>
<b>Field added. </b>
<code>bool bgpio_dir_inverted</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * reg_dir_out</code>
</li>
<li>
<b>Field added. </b>
<code>void * reg_dir_in</code>
</li>
<li>
<b>Field added. </b>
<code>bool bgpio_dir_unreadable</code>
</li>
<li>
<b>Field removed. </b>
<code>void * reg_dir</code>
</li>
<li>
<b>Field removed. </b>
<code>bool bgpio_dir_inverted</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool need_valid_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct gpio_chip *) init_valid_mask</code> ➡️ <code>int (*)(struct gpio_chip *, long unsigned int *, unsigned int) init_valid_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *) add_pin_ranges</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<code>u16 offset</code>
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
<code>struct fwnode_handle * fwnode</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, u32, long unsigned int) en_hw_timestamp</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, u32, long unsigned int) dis_hw_timestamp</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t bgpio_lock</code> ➡️ <code>raw_spinlock_t bgpio_lock</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_node * of_node</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int of_gpio_n_cells</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_node * of_node</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int of_gpio_n_cells</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_node * of_node</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int of_gpio_n_cells</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_node * of_node</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int of_gpio_n_cells</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gpio_chip *, const struct of_phandle_args *, u32 *) of_xlate</code>
</li>
</ul>
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
