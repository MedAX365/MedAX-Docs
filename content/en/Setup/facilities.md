---
title: "Facilities"
linkTitle: "Facilities"
weight: 4
date: 2018-07-30
description: >
  Learn how to create a facility and create service units in the facility.
---



## Creating a new facility

To create a new facility, you must fill in the main fields and the sub-fields that place in the general, service units, discount approve users and cash close tabs. The main fields are described in the following table.


| Field               | Description                                                                                                                               |  
|---------------------|:------------------------------------------------------------------------------------------------------------------------------------------|
| `Company`           | The company to which the facility is affiliated is selected                                                                               | 
| `Name`              | The name of the facility                                                                                                                  |  
| `Facility Type`     | Hospital, Clinic or Practice is selected                                                                                                  | 
| `Legal Name`        | The name identified for official reasons                                                                                                  |
| `Chief of Staff`    | The name of chief of staff                                                                                                                |
| `Patient Label`     | During patient admission, labels containing the patient's data are printed. In this field, the patient label design type can be selected. |
| `First Day of Week` | In some countries, the first working day may be different. Thanks to this field, the first working day of the week can be determined.     |

### General

#### *Regional Definition*

Carrier code is used for specifying and verifying a phone number with the right area code.

#### *Inventory Definitions*

Inventory management is carried out in healthcare facilities. Within the program, you have to connect a facility to a site that has an important place in terms of inventory management. Because, a warehouse place in a site. In this section, you need to choose a suitable **site** for the facility. Depending on this site, you must choose suitable warehouses  for the **medical supply warehouse** and **pharmacy warehouse** fields.

#### *Invoice Designs*

When a new patient is accepted, if the admission is an admission that does not require provision, the invoice session is opened directly. At the same time, if requested, the collection session can be opened instead of the invoice session. The invoicing transaction could be initiated in two ways. These are invoice mode or collection mode. By the help of **trans type**, whichever mode is requested, that mode can be preferred.

#### *New Born Definitions*

When a baby is born in the facility, you can set a **newborn default name** for that baby. You can also set the **newborn default citizenship** status. The newborn baby may need to be given health care. In this case, the baby can be served without a national ID. However, you can clarify how many days of service can be provided in this way in the **newborn days without national ID** field.

### Service Units

In the section, you can create a service unit. Service units created in a facility are connected to the warehouse assigned previously to the facility. Thus, material consumption is carried out on the service units. For this reason, when there is a consumption of a medical supply or a drug in these units, the inventory level in the warehouse connected to this service unit decreases by the amount of consumed material. 

You can also create an inpatient service unit and define rooms and beds for the inpatient unit. Then, the patients can be assigned to the beds and rooms. Besides, you can define equipments such as CR-Computerized Radiology, CT- Computerized Tomography or Magnetic Resonance for the radiology unit.

### Discount Approve Users

For an each facility, you can determine your staff member that has the privilege to approve the discount requests.

### Treasury Account

Account identification displays the bank account of the central treasury of the facility selected. Thus, the cash that is collected by the cashiers is deposited to these bank accounts within the facility at end of the shift. The identifications are directly connected to the treasury system of the Dynamics 365. You can define the currency and account identification in the section.







