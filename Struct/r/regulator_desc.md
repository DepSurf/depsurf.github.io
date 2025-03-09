# Struct: <code>regulator_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    bool continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int ramp_reg;
    unsigned int ramp_mask;
    const unsigned int * ramp_delay_table;
    unsigned int n_ramp_values;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int ramp_reg;
    unsigned int ramp_mask;
    const unsigned int * ramp_delay_table;
    unsigned int n_ramp_values;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int ramp_reg;
    unsigned int ramp_mask;
    const unsigned int * ramp_delay_table;
    unsigned int n_ramp_values;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int ramp_reg;
    unsigned int ramp_mask;
    const unsigned int * ramp_delay_table;
    unsigned int n_ramp_values;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int ramp_reg;
    unsigned int ramp_mask;
    const unsigned int * ramp_delay_table;
    unsigned int n_ramp_values;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    bool of_match_full_name;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct linear_range * linear_ranges;
    const unsigned int * linear_range_selectors_bitfield;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int ramp_reg;
    unsigned int ramp_mask;
    const unsigned int * ramp_delay_table;
    unsigned int n_ramp_values;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int poll_enabled_time;
    unsigned int (*)(unsigned int) of_map_mode;
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
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
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
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct regulator_desc {
    const char * name;
    const char * supply_name;
    const char * of_match;
    const char * regulators_node;
    int (*)(struct device_node *, const struct regulator_desc *, struct regulator_config *) of_parse_cb;
    int id;
    unsigned int continuous_voltage_range;
    unsigned int n_voltages;
    unsigned int n_current_limits;
    const struct regulator_ops * ops;
    int irq;
    enum regulator_type type;
    struct module * owner;
    unsigned int min_uV;
    unsigned int uV_step;
    unsigned int linear_min_sel;
    int fixed_uV;
    unsigned int ramp_delay;
    int min_dropout_uV;
    const struct regulator_linear_range * linear_ranges;
    const unsigned int * linear_range_selectors;
    int n_linear_ranges;
    const unsigned int * volt_table;
    const unsigned int * curr_table;
    unsigned int vsel_range_reg;
    unsigned int vsel_range_mask;
    unsigned int vsel_reg;
    unsigned int vsel_mask;
    unsigned int vsel_step;
    unsigned int csel_reg;
    unsigned int csel_mask;
    unsigned int apply_reg;
    unsigned int apply_bit;
    unsigned int enable_reg;
    unsigned int enable_mask;
    unsigned int enable_val;
    unsigned int disable_val;
    bool enable_is_inverted;
    unsigned int bypass_reg;
    unsigned int bypass_mask;
    unsigned int bypass_val_on;
    unsigned int bypass_val_off;
    unsigned int active_discharge_on;
    unsigned int active_discharge_off;
    unsigned int active_discharge_mask;
    unsigned int active_discharge_reg;
    unsigned int soft_start_reg;
    unsigned int soft_start_mask;
    unsigned int soft_start_val_on;
    unsigned int pull_down_reg;
    unsigned int pull_down_mask;
    unsigned int pull_down_val_on;
    unsigned int enable_time;
    unsigned int off_on_delay;
    unsigned int (*)(unsigned int) of_map_mode;
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
<code>unsigned int csel_reg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int csel_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int active_discharge_on</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int active_discharge_off</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int active_discharge_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int active_discharge_reg</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool continuous_voltage_range</code> ➡️ <code>unsigned int continuous_voltage_range</code>
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
<code>unsigned int soft_start_reg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int soft_start_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int soft_start_val_on</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pull_down_reg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pull_down_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pull_down_val_on</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const unsigned int * linear_range_selectors</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int vsel_range_reg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int vsel_range_mask</code>
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
<code>unsigned int n_current_limits</code>
</li>
<li>
<b>Field added. </b>
<code>const unsigned int * curr_table</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int vsel_step</code>
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
<b>Field type changed. </b>
<code>const struct regulator_linear_range * linear_ranges</code> ➡️ <code>const struct linear_range * linear_ranges</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool of_match_full_name</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int poll_enabled_time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int ramp_reg</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ramp_mask</code>
</li>
<li>
<b>Field added. </b>
<code>const unsigned int * ramp_delay_table</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_ramp_values</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const unsigned int * linear_range_selectors_bitfield</code>
</li>
<li>
<b>Field removed. </b>
<code>const unsigned int * linear_range_selectors</code>
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
