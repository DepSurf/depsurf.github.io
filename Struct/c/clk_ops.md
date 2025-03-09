# Struct: <code>clk_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    void (*)(struct clk_hw *) init;
    int (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    void (*)(struct clk_hw *) init;
    int (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    void (*)(struct clk_hw *) init;
    int (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    void (*)(struct clk_hw *) init;
    int (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    void (*)(struct clk_hw *) init;
    int (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    int (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *) terminate;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
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
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
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
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct clk_ops {
    int (*)(struct clk_hw *) prepare;
    void (*)(struct clk_hw *) unprepare;
    int (*)(struct clk_hw *) is_prepared;
    void (*)(struct clk_hw *) unprepare_unused;
    int (*)(struct clk_hw *) enable;
    void (*)(struct clk_hw *) disable;
    int (*)(struct clk_hw *) is_enabled;
    void (*)(struct clk_hw *) disable_unused;
    int (*)(struct clk_hw *) save_context;
    void (*)(struct clk_hw *) restore_context;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_rate;
    long int (*)(struct clk_hw *, long unsigned int, long unsigned int *) round_rate;
    int (*)(struct clk_hw *, struct clk_rate_request *) determine_rate;
    int (*)(struct clk_hw *, u8) set_parent;
    u8 (*)(struct clk_hw *) get_parent;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int) set_rate;
    int (*)(struct clk_hw *, long unsigned int, long unsigned int, u8) set_rate_and_parent;
    long unsigned int (*)(struct clk_hw *, long unsigned int) recalc_accuracy;
    int (*)(struct clk_hw *) get_phase;
    int (*)(struct clk_hw *, int) set_phase;
    int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle;
    int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle;
    void (*)(struct clk_hw *) init;
    void (*)(struct clk_hw *, struct dentry *) debug_init;
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
<b>Field type changed. </b>
<code>int (*)(struct clk_hw *, struct dentry *) debug_init</code> ➡️ <code>void (*)(struct clk_hw *, struct dentry *) debug_init</code>
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
<code>int (*)(struct clk_hw *) save_context</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct clk_hw *) restore_context</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct clk_hw *, struct clk_duty *) get_duty_cycle</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct clk_hw *, struct clk_duty *) set_duty_cycle</code>
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
<code>void (*)(struct clk_hw *) terminate</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct clk_hw *) init</code> ➡️ <code>int (*)(struct clk_hw *) init</code>
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
