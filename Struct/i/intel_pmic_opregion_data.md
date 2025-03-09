# Struct: <code>intel_pmic_opregion_data</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    int (*)(struct acpi_lpat_conversion_table *, int) lpat_raw_to_temp;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    int (*)(struct acpi_lpat_conversion_table *, int) lpat_raw_to_temp;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    int (*)(struct acpi_lpat_conversion_table *, int) lpat_raw_to_temp;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    int (*)(struct acpi_lpat_conversion_table *, int) lpat_raw_to_temp;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct intel_pmic_opregion_data {
    int (*)(struct regmap *, int, int, u64 *) get_power;
    int (*)(struct regmap *, int, int, bool) update_power;
    int (*)(struct regmap *, int) get_raw_temp;
    int (*)(struct regmap *, int, int) update_aux;
    int (*)(struct regmap *, int, int, u64 *) get_policy;
    int (*)(struct regmap *, int, int, int) update_policy;
    int (*)(struct regmap *, u16, u32, u32, u32) exec_mipi_pmic_seq_element;
    struct pmic_table * power_table;
    int power_table_count;
    struct pmic_table * thermal_table;
    int thermal_table_count;
    int pmic_i2c_address;
}
```
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct acpi_lpat_conversion_table *, int) lpat_raw_to_temp</code>
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
