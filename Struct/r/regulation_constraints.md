# Struct: <code>regulation_constraints</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int enable_time;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    int max_spread;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    int max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    struct notification_limit over_curr_limits;
    struct notification_limit over_voltage_limits;
    struct notification_limit under_voltage_limits;
    struct notification_limit temp_limits;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
    unsigned int over_current_detection;
    unsigned int over_voltage_detection;
    unsigned int under_voltage_detection;
    unsigned int over_temp_detection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    struct notification_limit over_curr_limits;
    struct notification_limit over_voltage_limits;
    struct notification_limit under_voltage_limits;
    struct notification_limit temp_limits;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
    unsigned int over_current_detection;
    unsigned int over_voltage_detection;
    unsigned int under_voltage_detection;
    unsigned int over_temp_detection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    struct notification_limit over_curr_limits;
    struct notification_limit over_voltage_limits;
    struct notification_limit under_voltage_limits;
    struct notification_limit temp_limits;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
    unsigned int over_current_detection;
    unsigned int over_voltage_detection;
    unsigned int under_voltage_detection;
    unsigned int over_temp_detection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    struct notification_limit over_curr_limits;
    struct notification_limit over_voltage_limits;
    struct notification_limit under_voltage_limits;
    struct notification_limit temp_limits;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
    unsigned int over_current_detection;
    unsigned int over_voltage_detection;
    unsigned int under_voltage_detection;
    unsigned int over_temp_detection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    struct notification_limit over_curr_limits;
    struct notification_limit over_voltage_limits;
    struct notification_limit under_voltage_limits;
    struct notification_limit temp_limits;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int uv_less_critical_window_ms;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int system_critical;
    unsigned int over_current_protection;
    unsigned int over_current_detection;
    unsigned int over_voltage_detection;
    unsigned int under_voltage_detection;
    unsigned int over_temp_detection;
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
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
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
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regulation_constraints {
    const char * name;
    int min_uV;
    int max_uV;
    int uV_offset;
    int min_uA;
    int max_uA;
    int ilim_uA;
    int system_load;
    u32 * max_spread;
    int max_uV_step;
    unsigned int valid_modes_mask;
    unsigned int valid_ops_mask;
    int input_uV;
    struct regulator_state state_disk;
    struct regulator_state state_mem;
    struct regulator_state state_standby;
    suspend_state_t initial_state;
    unsigned int initial_mode;
    unsigned int ramp_delay;
    unsigned int settling_time;
    unsigned int settling_time_up;
    unsigned int settling_time_down;
    unsigned int enable_time;
    unsigned int active_discharge;
    unsigned int always_on;
    unsigned int boot_on;
    unsigned int apply_uV;
    unsigned int ramp_disable;
    unsigned int soft_start;
    unsigned int pull_down;
    unsigned int over_current_protection;
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
<code>unsigned int active_discharge</code>
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
<b>Field added. </b>
<code>unsigned int settling_time</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int settling_time_up</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int settling_time_down</code>
</li>
</ul>
</details>
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
<code>int max_spread</code>
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
<code>int max_uV_step</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int max_spread</code> ➡️ <code>u32 * max_spread</code>
</li>
</ul>
</details>
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
<code>struct notification_limit over_curr_limits</code>
</li>
<li>
<b>Field added. </b>
<code>struct notification_limit over_voltage_limits</code>
</li>
<li>
<b>Field added. </b>
<code>struct notification_limit under_voltage_limits</code>
</li>
<li>
<b>Field added. </b>
<code>struct notification_limit temp_limits</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int over_current_detection</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int over_voltage_detection</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int under_voltage_detection</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int over_temp_detection</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int uv_less_critical_window_ms</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int system_critical</code>
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
