# Data Dictionary: Transit Predictive Maintenance (TPM) Dataset

This document lists the column structures and data types for all cleaned dataset files.

##  File: `/cleaned_null_test_labels.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `class_label` | `int64` | Target variable / label / time-to-event |

---

##  File: `/cleaned_null_test_operational_readouts.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `time_step` | `float64` | Operational sensor readout / feature |
| `171_0` | `float64` | Operational sensor readout / feature |
| `666_0` | `float64` | Operational sensor readout / feature |
| `427_0` | `float64` | Operational sensor readout / feature |
| `837_0` | `float64` | Operational sensor readout / feature |
| `167_0` | `float64` | Operational sensor readout / feature |
| `167_1` | `float64` | Operational sensor readout / feature |
| `167_2` | `float64` | Operational sensor readout / feature |
| `167_3` | `float64` | Operational sensor readout / feature |
| `167_4` | `float64` | Operational sensor readout / feature |
| `167_5` | `float64` | Operational sensor readout / feature |
| `167_6` | `float64` | Operational sensor readout / feature |
| `167_7` | `float64` | Operational sensor readout / feature |
| `167_8` | `float64` | Operational sensor readout / feature |
| `167_9` | `float64` | Operational sensor readout / feature |
| `309_0` | `float64` | Operational sensor readout / feature |
| `272_0` | `float64` | Operational sensor readout / feature |
| `272_1` | `float64` | Operational sensor readout / feature |
| `272_2` | `float64` | Operational sensor readout / feature |
| `272_3` | `float64` | Operational sensor readout / feature |
| `272_4` | `float64` | Operational sensor readout / feature |
| `272_5` | `float64` | Operational sensor readout / feature |
| `272_6` | `float64` | Operational sensor readout / feature |
| `272_7` | `float64` | Operational sensor readout / feature |
| `272_8` | `float64` | Operational sensor readout / feature |
| `272_9` | `float64` | Operational sensor readout / feature |
| `835_0` | `float64` | Operational sensor readout / feature |
| `370_0` | `float64` | Operational sensor readout / feature |
| `291_0` | `float64` | Operational sensor readout / feature |
| `291_1` | `float64` | Operational sensor readout / feature |
| `291_2` | `float64` | Operational sensor readout / feature |
| `291_3` | `float64` | Operational sensor readout / feature |
| `291_4` | `float64` | Operational sensor readout / feature |
| `291_5` | `float64` | Operational sensor readout / feature |
| `291_6` | `float64` | Operational sensor readout / feature |
| `291_7` | `float64` | Operational sensor readout / feature |
| `291_8` | `float64` | Operational sensor readout / feature |
| `291_9` | `float64` | Operational sensor readout / feature |
| `291_10` | `float64` | Operational sensor readout / feature |
| `158_0` | `float64` | Operational sensor readout / feature |
| `158_1` | `float64` | Operational sensor readout / feature |
| `158_2` | `float64` | Operational sensor readout / feature |
| `158_3` | `float64` | Operational sensor readout / feature |
| `158_4` | `float64` | Operational sensor readout / feature |
| `158_5` | `float64` | Operational sensor readout / feature |
| `158_6` | `float64` | Operational sensor readout / feature |
| `158_7` | `float64` | Operational sensor readout / feature |
| `158_8` | `float64` | Operational sensor readout / feature |
| `158_9` | `float64` | Operational sensor readout / feature |
| `100_0` | `float64` | Operational sensor readout / feature |
| `459_0` | `float64` | Operational sensor readout / feature |
| `459_1` | `float64` | Operational sensor readout / feature |
| `459_2` | `float64` | Operational sensor readout / feature |
| `459_3` | `float64` | Operational sensor readout / feature |
| `459_4` | `float64` | Operational sensor readout / feature |
| `459_5` | `float64` | Operational sensor readout / feature |
| `459_6` | `float64` | Operational sensor readout / feature |
| `459_7` | `float64` | Operational sensor readout / feature |
| `459_8` | `float64` | Operational sensor readout / feature |
| `459_9` | `float64` | Operational sensor readout / feature |
| `459_10` | `float64` | Operational sensor readout / feature |
| `459_11` | `float64` | Operational sensor readout / feature |
| `459_12` | `float64` | Operational sensor readout / feature |
| `459_13` | `float64` | Operational sensor readout / feature |
| `459_14` | `float64` | Operational sensor readout / feature |
| `459_15` | `float64` | Operational sensor readout / feature |
| `459_16` | `float64` | Operational sensor readout / feature |
| `459_17` | `float64` | Operational sensor readout / feature |
| `459_18` | `float64` | Operational sensor readout / feature |
| `459_19` | `float64` | Operational sensor readout / feature |
| `397_0` | `float64` | Operational sensor readout / feature |
| `397_1` | `float64` | Operational sensor readout / feature |
| `397_2` | `float64` | Operational sensor readout / feature |
| `397_3` | `float64` | Operational sensor readout / feature |
| `397_4` | `float64` | Operational sensor readout / feature |
| `397_5` | `float64` | Operational sensor readout / feature |
| `397_6` | `float64` | Operational sensor readout / feature |
| `397_7` | `float64` | Operational sensor readout / feature |
| `397_8` | `float64` | Operational sensor readout / feature |
| `397_9` | `float64` | Operational sensor readout / feature |
| `397_10` | `float64` | Operational sensor readout / feature |
| `397_11` | `float64` | Operational sensor readout / feature |
| `397_12` | `float64` | Operational sensor readout / feature |
| `397_13` | `float64` | Operational sensor readout / feature |
| `397_14` | `float64` | Operational sensor readout / feature |
| `397_15` | `float64` | Operational sensor readout / feature |
| `397_16` | `float64` | Operational sensor readout / feature |
| `397_17` | `float64` | Operational sensor readout / feature |
| `397_18` | `float64` | Operational sensor readout / feature |
| `397_19` | `float64` | Operational sensor readout / feature |
| `397_20` | `float64` | Operational sensor readout / feature |
| `397_21` | `float64` | Operational sensor readout / feature |
| `397_22` | `float64` | Operational sensor readout / feature |
| `397_23` | `float64` | Operational sensor readout / feature |
| `397_24` | `float64` | Operational sensor readout / feature |
| `397_25` | `float64` | Operational sensor readout / feature |
| `397_26` | `float64` | Operational sensor readout / feature |
| `397_27` | `float64` | Operational sensor readout / feature |
| `397_28` | `float64` | Operational sensor readout / feature |
| `397_29` | `float64` | Operational sensor readout / feature |
| `397_30` | `float64` | Operational sensor readout / feature |
| `397_31` | `float64` | Operational sensor readout / feature |
| `397_32` | `float64` | Operational sensor readout / feature |
| `397_33` | `float64` | Operational sensor readout / feature |
| `397_34` | `float64` | Operational sensor readout / feature |
| `397_35` | `float64` | Operational sensor readout / feature |

---

##  File: `/cleaned_null_test_specifications.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `Spec_0` | `object` | Technical specification data |
| `Spec_1` | `object` | Technical specification data |
| `Spec_2` | `object` | Technical specification data |
| `Spec_3` | `object` | Technical specification data |
| `Spec_4` | `object` | Technical specification data |
| `Spec_5` | `object` | Technical specification data |
| `Spec_6` | `object` | Technical specification data |
| `Spec_7` | `object` | Technical specification data |

---

##  File: `/cleaned_null_train_operational_readouts.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `time_step` | `float64` | Operational sensor readout / feature |
| `171_0` | `float64` | Operational sensor readout / feature |
| `666_0` | `float64` | Operational sensor readout / feature |
| `427_0` | `float64` | Operational sensor readout / feature |
| `837_0` | `float64` | Operational sensor readout / feature |
| `167_0` | `float64` | Operational sensor readout / feature |
| `167_1` | `float64` | Operational sensor readout / feature |
| `167_2` | `float64` | Operational sensor readout / feature |
| `167_3` | `float64` | Operational sensor readout / feature |
| `167_4` | `float64` | Operational sensor readout / feature |
| `167_5` | `float64` | Operational sensor readout / feature |
| `167_6` | `float64` | Operational sensor readout / feature |
| `167_7` | `float64` | Operational sensor readout / feature |
| `167_8` | `float64` | Operational sensor readout / feature |
| `167_9` | `float64` | Operational sensor readout / feature |
| `309_0` | `float64` | Operational sensor readout / feature |
| `272_0` | `float64` | Operational sensor readout / feature |
| `272_1` | `float64` | Operational sensor readout / feature |
| `272_2` | `float64` | Operational sensor readout / feature |
| `272_3` | `float64` | Operational sensor readout / feature |
| `272_4` | `float64` | Operational sensor readout / feature |
| `272_5` | `float64` | Operational sensor readout / feature |
| `272_6` | `float64` | Operational sensor readout / feature |
| `272_7` | `float64` | Operational sensor readout / feature |
| `272_8` | `float64` | Operational sensor readout / feature |
| `272_9` | `float64` | Operational sensor readout / feature |
| `835_0` | `float64` | Operational sensor readout / feature |
| `370_0` | `float64` | Operational sensor readout / feature |
| `291_0` | `float64` | Operational sensor readout / feature |
| `291_1` | `float64` | Operational sensor readout / feature |
| `291_2` | `float64` | Operational sensor readout / feature |
| `291_3` | `float64` | Operational sensor readout / feature |
| `291_4` | `float64` | Operational sensor readout / feature |
| `291_5` | `float64` | Operational sensor readout / feature |
| `291_6` | `float64` | Operational sensor readout / feature |
| `291_7` | `float64` | Operational sensor readout / feature |
| `291_8` | `float64` | Operational sensor readout / feature |
| `291_9` | `float64` | Operational sensor readout / feature |
| `291_10` | `float64` | Operational sensor readout / feature |
| `158_0` | `float64` | Operational sensor readout / feature |
| `158_1` | `float64` | Operational sensor readout / feature |
| `158_2` | `float64` | Operational sensor readout / feature |
| `158_3` | `float64` | Operational sensor readout / feature |
| `158_4` | `float64` | Operational sensor readout / feature |
| `158_5` | `float64` | Operational sensor readout / feature |
| `158_6` | `float64` | Operational sensor readout / feature |
| `158_7` | `float64` | Operational sensor readout / feature |
| `158_8` | `float64` | Operational sensor readout / feature |
| `158_9` | `float64` | Operational sensor readout / feature |
| `100_0` | `float64` | Operational sensor readout / feature |
| `459_0` | `float64` | Operational sensor readout / feature |
| `459_1` | `float64` | Operational sensor readout / feature |
| `459_2` | `float64` | Operational sensor readout / feature |
| `459_3` | `float64` | Operational sensor readout / feature |
| `459_4` | `float64` | Operational sensor readout / feature |
| `459_5` | `float64` | Operational sensor readout / feature |
| `459_6` | `float64` | Operational sensor readout / feature |
| `459_7` | `float64` | Operational sensor readout / feature |
| `459_8` | `float64` | Operational sensor readout / feature |
| `459_9` | `float64` | Operational sensor readout / feature |
| `459_10` | `float64` | Operational sensor readout / feature |
| `459_11` | `float64` | Operational sensor readout / feature |
| `459_12` | `float64` | Operational sensor readout / feature |
| `459_13` | `float64` | Operational sensor readout / feature |
| `459_14` | `float64` | Operational sensor readout / feature |
| `459_15` | `float64` | Operational sensor readout / feature |
| `459_16` | `float64` | Operational sensor readout / feature |
| `459_17` | `float64` | Operational sensor readout / feature |
| `459_18` | `float64` | Operational sensor readout / feature |
| `459_19` | `float64` | Operational sensor readout / feature |
| `397_0` | `float64` | Operational sensor readout / feature |
| `397_1` | `float64` | Operational sensor readout / feature |
| `397_2` | `float64` | Operational sensor readout / feature |
| `397_3` | `float64` | Operational sensor readout / feature |
| `397_4` | `float64` | Operational sensor readout / feature |
| `397_5` | `float64` | Operational sensor readout / feature |
| `397_6` | `float64` | Operational sensor readout / feature |
| `397_7` | `float64` | Operational sensor readout / feature |
| `397_8` | `float64` | Operational sensor readout / feature |
| `397_9` | `float64` | Operational sensor readout / feature |
| `397_10` | `float64` | Operational sensor readout / feature |
| `397_11` | `float64` | Operational sensor readout / feature |
| `397_12` | `float64` | Operational sensor readout / feature |
| `397_13` | `float64` | Operational sensor readout / feature |
| `397_14` | `float64` | Operational sensor readout / feature |
| `397_15` | `float64` | Operational sensor readout / feature |
| `397_16` | `float64` | Operational sensor readout / feature |
| `397_17` | `float64` | Operational sensor readout / feature |
| `397_18` | `float64` | Operational sensor readout / feature |
| `397_19` | `float64` | Operational sensor readout / feature |
| `397_20` | `float64` | Operational sensor readout / feature |
| `397_21` | `float64` | Operational sensor readout / feature |
| `397_22` | `float64` | Operational sensor readout / feature |
| `397_23` | `float64` | Operational sensor readout / feature |
| `397_24` | `float64` | Operational sensor readout / feature |
| `397_25` | `float64` | Operational sensor readout / feature |
| `397_26` | `float64` | Operational sensor readout / feature |
| `397_27` | `float64` | Operational sensor readout / feature |
| `397_28` | `float64` | Operational sensor readout / feature |
| `397_29` | `float64` | Operational sensor readout / feature |
| `397_30` | `float64` | Operational sensor readout / feature |
| `397_31` | `float64` | Operational sensor readout / feature |
| `397_32` | `float64` | Operational sensor readout / feature |
| `397_33` | `float64` | Operational sensor readout / feature |
| `397_34` | `float64` | Operational sensor readout / feature |
| `397_35` | `float64` | Operational sensor readout / feature |

---

##  File: `/cleaned_null_train_specifications.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `Spec_0` | `object` | Technical specification data |
| `Spec_1` | `object` | Technical specification data |
| `Spec_2` | `object` | Technical specification data |
| `Spec_3` | `object` | Technical specification data |
| `Spec_4` | `object` | Technical specification data |
| `Spec_5` | `object` | Technical specification data |
| `Spec_6` | `object` | Technical specification data |
| `Spec_7` | `object` | Technical specification data |

---

##  File: `/cleaned_null_train_tte.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `length_of_study_time_step` | `float64` | Operational sensor readout / feature |
| `in_study_repair` | `int64` | Operational sensor readout / feature |

---

##  File: `/cleaned_null_validation_labels.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `class_label` | `int64` | Target variable / label / time-to-event |

---

##  File: `/cleaned_null_validation_operational_readouts.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `time_step` | `float64` | Operational sensor readout / feature |
| `171_0` | `float64` | Operational sensor readout / feature |
| `666_0` | `float64` | Operational sensor readout / feature |
| `427_0` | `float64` | Operational sensor readout / feature |
| `837_0` | `float64` | Operational sensor readout / feature |
| `167_0` | `float64` | Operational sensor readout / feature |
| `167_1` | `float64` | Operational sensor readout / feature |
| `167_2` | `float64` | Operational sensor readout / feature |
| `167_3` | `float64` | Operational sensor readout / feature |
| `167_4` | `float64` | Operational sensor readout / feature |
| `167_5` | `float64` | Operational sensor readout / feature |
| `167_6` | `float64` | Operational sensor readout / feature |
| `167_7` | `float64` | Operational sensor readout / feature |
| `167_8` | `float64` | Operational sensor readout / feature |
| `167_9` | `float64` | Operational sensor readout / feature |
| `309_0` | `float64` | Operational sensor readout / feature |
| `272_0` | `float64` | Operational sensor readout / feature |
| `272_1` | `float64` | Operational sensor readout / feature |
| `272_2` | `float64` | Operational sensor readout / feature |
| `272_3` | `float64` | Operational sensor readout / feature |
| `272_4` | `float64` | Operational sensor readout / feature |
| `272_5` | `float64` | Operational sensor readout / feature |
| `272_6` | `float64` | Operational sensor readout / feature |
| `272_7` | `float64` | Operational sensor readout / feature |
| `272_8` | `float64` | Operational sensor readout / feature |
| `272_9` | `float64` | Operational sensor readout / feature |
| `835_0` | `float64` | Operational sensor readout / feature |
| `370_0` | `float64` | Operational sensor readout / feature |
| `291_0` | `float64` | Operational sensor readout / feature |
| `291_1` | `float64` | Operational sensor readout / feature |
| `291_2` | `float64` | Operational sensor readout / feature |
| `291_3` | `float64` | Operational sensor readout / feature |
| `291_4` | `float64` | Operational sensor readout / feature |
| `291_5` | `float64` | Operational sensor readout / feature |
| `291_6` | `float64` | Operational sensor readout / feature |
| `291_7` | `float64` | Operational sensor readout / feature |
| `291_8` | `float64` | Operational sensor readout / feature |
| `291_9` | `float64` | Operational sensor readout / feature |
| `291_10` | `float64` | Operational sensor readout / feature |
| `158_0` | `float64` | Operational sensor readout / feature |
| `158_1` | `float64` | Operational sensor readout / feature |
| `158_2` | `float64` | Operational sensor readout / feature |
| `158_3` | `float64` | Operational sensor readout / feature |
| `158_4` | `float64` | Operational sensor readout / feature |
| `158_5` | `float64` | Operational sensor readout / feature |
| `158_6` | `float64` | Operational sensor readout / feature |
| `158_7` | `float64` | Operational sensor readout / feature |
| `158_8` | `float64` | Operational sensor readout / feature |
| `158_9` | `float64` | Operational sensor readout / feature |
| `100_0` | `float64` | Operational sensor readout / feature |
| `459_0` | `float64` | Operational sensor readout / feature |
| `459_1` | `float64` | Operational sensor readout / feature |
| `459_2` | `float64` | Operational sensor readout / feature |
| `459_3` | `float64` | Operational sensor readout / feature |
| `459_4` | `float64` | Operational sensor readout / feature |
| `459_5` | `float64` | Operational sensor readout / feature |
| `459_6` | `float64` | Operational sensor readout / feature |
| `459_7` | `float64` | Operational sensor readout / feature |
| `459_8` | `float64` | Operational sensor readout / feature |
| `459_9` | `float64` | Operational sensor readout / feature |
| `459_10` | `float64` | Operational sensor readout / feature |
| `459_11` | `float64` | Operational sensor readout / feature |
| `459_12` | `float64` | Operational sensor readout / feature |
| `459_13` | `float64` | Operational sensor readout / feature |
| `459_14` | `float64` | Operational sensor readout / feature |
| `459_15` | `float64` | Operational sensor readout / feature |
| `459_16` | `float64` | Operational sensor readout / feature |
| `459_17` | `float64` | Operational sensor readout / feature |
| `459_18` | `float64` | Operational sensor readout / feature |
| `459_19` | `float64` | Operational sensor readout / feature |
| `397_0` | `float64` | Operational sensor readout / feature |
| `397_1` | `float64` | Operational sensor readout / feature |
| `397_2` | `float64` | Operational sensor readout / feature |
| `397_3` | `float64` | Operational sensor readout / feature |
| `397_4` | `float64` | Operational sensor readout / feature |
| `397_5` | `float64` | Operational sensor readout / feature |
| `397_6` | `float64` | Operational sensor readout / feature |
| `397_7` | `float64` | Operational sensor readout / feature |
| `397_8` | `float64` | Operational sensor readout / feature |
| `397_9` | `float64` | Operational sensor readout / feature |
| `397_10` | `float64` | Operational sensor readout / feature |
| `397_11` | `float64` | Operational sensor readout / feature |
| `397_12` | `float64` | Operational sensor readout / feature |
| `397_13` | `float64` | Operational sensor readout / feature |
| `397_14` | `float64` | Operational sensor readout / feature |
| `397_15` | `float64` | Operational sensor readout / feature |
| `397_16` | `float64` | Operational sensor readout / feature |
| `397_17` | `float64` | Operational sensor readout / feature |
| `397_18` | `float64` | Operational sensor readout / feature |
| `397_19` | `float64` | Operational sensor readout / feature |
| `397_20` | `float64` | Operational sensor readout / feature |
| `397_21` | `float64` | Operational sensor readout / feature |
| `397_22` | `float64` | Operational sensor readout / feature |
| `397_23` | `float64` | Operational sensor readout / feature |
| `397_24` | `float64` | Operational sensor readout / feature |
| `397_25` | `float64` | Operational sensor readout / feature |
| `397_26` | `float64` | Operational sensor readout / feature |
| `397_27` | `float64` | Operational sensor readout / feature |
| `397_28` | `float64` | Operational sensor readout / feature |
| `397_29` | `float64` | Operational sensor readout / feature |
| `397_30` | `float64` | Operational sensor readout / feature |
| `397_31` | `float64` | Operational sensor readout / feature |
| `397_32` | `float64` | Operational sensor readout / feature |
| `397_33` | `float64` | Operational sensor readout / feature |
| `397_34` | `float64` | Operational sensor readout / feature |
| `397_35` | `float64` | Operational sensor readout / feature |

---

##  File: `/cleaned_null_validation_specifications.csv`

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `vehicle_id` | `int64` | Unique Identifier (ID) |
| `Spec_0` | `object` | Technical specification data |
| `Spec_1` | `object` | Technical specification data |
| `Spec_2` | `object` | Technical specification data |
| `Spec_3` | `object` | Technical specification data |
| `Spec_4` | `object` | Technical specification data |
| `Spec_5` | `object` | Technical specification data |
| `Spec_6` | `object` | Technical specification data |
| `Spec_7` | `object` | Technical specification data |

---

