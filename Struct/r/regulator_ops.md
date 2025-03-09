# Struct: <code>regulator_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume_early;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *, int, int, bool) set_over_current_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_over_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_under_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_thermal_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *, int, int, bool) set_over_current_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_over_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_under_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_thermal_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *, int, int, bool) set_over_current_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_over_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_under_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_thermal_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *, int, int, bool) set_over_current_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_over_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_under_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_thermal_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *, int, int, bool) set_over_current_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_over_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_under_voltage_protection;
    int (*)(struct regulator_dev *, int, int, bool) set_thermal_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
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
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
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
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regulator_ops {
    int (*)(struct regulator_dev *, unsigned int) list_voltage;
    int (*)(struct regulator_dev *, int, int, unsigned int *) set_voltage;
    int (*)(struct regulator_dev *, int, int) map_voltage;
    int (*)(struct regulator_dev *, unsigned int) set_voltage_sel;
    int (*)(struct regulator_dev *) get_voltage;
    int (*)(struct regulator_dev *) get_voltage_sel;
    int (*)(struct regulator_dev *, int, int) set_current_limit;
    int (*)(struct regulator_dev *) get_current_limit;
    int (*)(struct regulator_dev *, int) set_input_current_limit;
    int (*)(struct regulator_dev *) set_over_current_protection;
    int (*)(struct regulator_dev *, bool) set_active_discharge;
    int (*)(struct regulator_dev *) enable;
    int (*)(struct regulator_dev *) disable;
    int (*)(struct regulator_dev *) is_enabled;
    int (*)(struct regulator_dev *, unsigned int) set_mode;
    unsigned int (*)(struct regulator_dev *) get_mode;
    int (*)(struct regulator_dev *, unsigned int *) get_error_flags;
    int (*)(struct regulator_dev *) enable_time;
    int (*)(struct regulator_dev *, int) set_ramp_delay;
    int (*)(struct regulator_dev *, int, int) set_voltage_time;
    int (*)(struct regulator_dev *, unsigned int, unsigned int) set_voltage_time_sel;
    int (*)(struct regulator_dev *) set_soft_start;
    int (*)(struct regulator_dev *) get_status;
    unsigned int (*)(struct regulator_dev *, int, int, int) get_optimum_mode;
    int (*)(struct regulator_dev *, int) set_load;
    int (*)(struct regulator_dev *, bool) set_bypass;
    int (*)(struct regulator_dev *, bool *) get_bypass;
    int (*)(struct regulator_dev *, int) set_suspend_voltage;
    int (*)(struct regulator_dev *) set_suspend_enable;
    int (*)(struct regulator_dev *) set_suspend_disable;
    int (*)(struct regulator_dev *, unsigned int) set_suspend_mode;
    int (*)(struct regulator_dev *) resume;
    int (*)(struct regulator_dev *) set_pull_down;
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
<code>int (*)(struct regulator_dev *, bool) set_active_discharge</code>
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
<code>int (*)(struct regulator_dev *, unsigned int *) get_error_flags</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct regulator_dev *, int, int) set_voltage_time</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>int (*)(struct regulator_dev *) resume_early</code>
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
<code>int (*)(struct regulator_dev *) resume</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct regulator_dev *) resume_early</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<code>int (*)(struct regulator_dev *, int, int, bool) set_over_voltage_protection</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct regulator_dev *, int, int, bool) set_under_voltage_protection</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct regulator_dev *, int, int, bool) set_thermal_protection</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct regulator_dev *) set_over_current_protection</code> ➡️ <code>int (*)(struct regulator_dev *, int, int, bool) set_over_current_protection</code>
</li>
</ul>
</details>
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
