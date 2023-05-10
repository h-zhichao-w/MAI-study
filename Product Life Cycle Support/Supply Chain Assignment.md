# Supply Chain Assignment

Student Name: Zhichao Wang$^1$, and Yuxiao Cheng$^2$

Student E-mail: 1:hansen_wong@sjtu.edu.cn, 2:germenking@sjtu.edu.cn

[toc]

## 1 BOM analysis

To make a supply chain, the materials needed must be determined first. A simple BOM is made to help understand what materials would be taken into consideration in the following supply chain analysis.

| Component Name           | Level & Code | Quantity | Unit  | Description                                                  |
| ------------------------ | ------------ | -------- | ----- | ------------------------------------------------------------ |
| Tabletop                 | 0-1          | 1        | set   | Made of wood, object-bearing, waterproof, non-conductive and non-heat-conductive. |
| Wireless Charging Module | 0-2          | 1        | set   | Get power from the mains, have a stand to hold the phone, and charge wirelessly via a built-in coil. |
| Electromagnetic Coil     | 0-2-1        | 1        | set   | Copper, generate changing electromagnetic fields for wireless charging. |
| Charging Controller      | 0-2-2        | 1        | set   | Electronic components for current and power monitoring and protection of circuits. |
| Mobile phone stand       | 0-2-3        | 1        | set   | Plastic, for fixing the handset, with an embedded coil.      |
| Charging Cable           | 0-2-4        | 1        | Meter | USB Type-A to USB Type-C or Lightning cable to connect the wireless charging module to the power source power |
| Power Supply             | 0-2-5        | 1        | set   | AC or USB power adapter, depending on the wireless charging module used |
| Table Legs               | 0-3          | 4        | set   | Wooden, load-bearing, with carving to increase aesthetics    |
| Screws and Fasteners     | 0-4          | 20       | set   | Various screws and fasteners for assembly                    |
| Packaging Material       | 0-5          | 1        | set   | Boxes, foam, manual, and protective coverings for shipping   |

## 2 Suppliers

| Name                                                         | Product                                   | Contact                    |
| ------------------------------------------------------------ | ----------------------------------------- | -------------------------- |
| [Shanghai Yihuang Wood Industry Co., Ltd.](https://shyihuang.en.alibaba.com/) | Custom wood products                      | marsjiang@yihuang-wood.com |
| [Huaqiang Electronic World](http://www.szhq.com/electronic.html) | Electronic components                     | TEL: 0755-6686 1701        |
| [Shantou Yachi Trading Co.](http://stsyqsm.sitongzixun.com/) | Mobile stand and wireless charging module | TEL: 86 0754 88886519      |
| [Shenzhen Yingda Hardware Products Co.](http://2586989.b2b.liebiao.com/) | Metal hardware (nuts and bolts)           | TEL: 13714339738           |
| [Guangzhou Bosing Paper Printing & Packaging Co., Ltd](https://www.gzbosing.com/) | Packing and printing                      | bosing@bosing.cn           |

## 3 Spare parts prices 

Generally, it's recommended to have at least 5-10% extra components on hand for the production run, which means an additional 50-100 pieces of component (5-10% of 1,000) as spares should be considered. For the case of cost reduction, in this lab we would prepare enough components for 1050 pieces batch of product.

| Component Name           | Level & Code | Quantity | Wholesale Unit Price | Total Wholesale Price |
| ------------------------ | ------------ | -------- | ---------------------| ----------------------|
| **Tabletop**             | 0-1          | 1,050    | **\$40**                  | **\$42,000**               |
| **Wireless Charging Module** | 0-2          | 1,050    | **\$4**                  | **\$4,200**        |
| Electromagnetic Coil     | 0-2-1        | 1,050    | \$0.1                 | \$105              |
| Charging Controller      | 0-2-2        | 1,050    | \$0.5                 | \$525             |
| Mobile phone stand       | 0-2-3        | 1,050    | \$2                   | \$2,100                |
| Charging Cable           | 0-2-4        | 1,050    | \$0.6                 | \$630              |
| Power Supply             | 0-2-5        | 1,050    | \$0.8               | \$840              |
| **Table Legs**           | 0-3          | 4,200    | **\$10**                  | **\$42,000**       |
| **Screws and Fasteners** | 0-4          | 21,000   | **\$0.1**                | **\$2,100**                |
| **Packaging Material**   | 0-5          | 1050 | **\$1.8**                | **\$1,890**              |
| **Total**                    | /            | 1050     | **\$85.9** |  **\$90,195** |

## 4 Shipment price

The density of the produced wood: 850 kg/m$^3$

The volume of the wood: Tabletop - $1.8\times1\times0.25-1.7\times0.9\times0.15=0.22$ m$^3$; Table leg - $0.25\pi\times0.2^2\times0.65=0.02$ m$^3$; In all, the weight would be 255 kg for the wood needed for one table.

To prepare for 1050 tables, 267.75 tons of wood would be needed. The supplier of the wood is in the same city, Shanghai, as our factory. Thus, the shipment price for the wood would be (assuming an average delivery distance of 50 km and an average transportation cost of $0.07 per tonne-kilometer) :

- Total weight of wood: 267.75 tons
- Total transportation distance: 2 x 50 km = 100 km (delivery and return trip)
- Total tonne-kilometers: 267.75 tons x 100 km = 26,775 tonne-km
- Estimated transportation cost: \$0.07 per tonne-km x 26,775 tonne-km = \$1874.25

The shipment of screws, fasteners, and wireless charging modules can be neglected due to the low weight, small volume, and shipping-free agreement with the suppliers.

To deliver the packing materials needed,

* Total transportation distance: 16,000 km
* Total weight: 54,010 kg = 54.01 ton
*  Total tonne-kilometers: 54.01 tons x 16,000 km = 864,160 tonne-km
* Estimated transportation cost: \$0.07 per tonne-km x 864,160 tonne-km = \$60,491.2

Therefore, the total shipping price is estimated to be \$62,365.45

## 5 Delivery Time

Manufacture time: For the suppliers to prepare the materials we need, it would take at most one week.  Considering about the time of queuing, it would take about three weeks to have all the materials ready. 

Delivery time: Road transport from Guangdong to Shanghai takes about three days.

Assembly time: Due to the large weight of the product, it is not wise to assemble all the components in our factory and deliver the whole table to the customer directly. Instead, some easy packing work will be done including packing up the screws and fasteners, packing up the tabletops and table legs, and assembling the wireless charging modules. There is no clear time limit for this item, it can be done while operating, but it takes one day to prepare the business balance

Delivery time (to customer): Within one day.

Assembly time (at the customer): About one hour.

In all, the entire production and sales cycle takes three to four weeks.

## 6 Approximate inventory size

Suppose the stacking height limit for each layer is 2 meters, and the storage structure is three layers. For each storage structure with an area of 3 meters times 3 meters, it can hold 120 tabletops. 9 storage structures are enough for all 1050 tabletops. Similarly, two storage structures are enough for all table legs and one is enough for all other components. In order to guarantee the turnover margin and to distinguish between packed and unpacked materials, we need a total of 24 storage structures. Including the aisle area, a minimum of 486 m$^2$ of space is required. Considering extra working places, office and meeting room are needed, a sum of 700 m$^2$ of space is required. 

## 7 Final price

| Item          | Value  |
| ------------- | ------ |
| Part cost     | \$85.9 |
| Shipment      | \$62.4 |
| Inventory     | \$7    |
| Profitability | 40%    |
| Final price   | \$388  |



[^bignote]: 
