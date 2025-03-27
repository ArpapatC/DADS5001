# DADS5001
E-Government Development Index (EGDI) 2024<br/>
<br/>
สำนักงานพัฒนารัฐบาลดิจิทัล (องค์การมหาชน) หรือ DGA ได้จัดทำ แผนพัฒนารัฐบาลดิจิทัลของประเทศไทย พ.ศ. 2566 – 2570 โดยตั้งเป้าหมายในการยกระดับ ดัชนีรัฐบาลอิเล็กทรอนิกส์ (E-Government Development Index: EGDI) ให้ได้อันดับไม่ต่ำกว่าอันดับที่ 40 ของโลก ภายในปี 2570 ซึ่งผลที่จัดทำล่าสุด EGDI 2024 ในปี 2567 ประเทศไทยอยู่ที่อันดับที่ 52 ของโลก <br/>
<br/>
เพื่อให้บรรลุเป้าหมายดังกล่าว งานชิ้นนี้จึงมีวัตถุประสงค์ในการวิเคราะห์ว่า ประเทศไทยควรมุ่งเน้นการยกระดับดัชนีย่อยใด ที่จะส่งผลต่อการเพิ่มอันดับ EGDI อย่างมีประสิทธิภาพ

# Part 1: Overall Analysis of E-Government Development Index (EGDI), Online Service Index (OSI), Telecommunications Infrastructure Index (TII), and Human capital Index (HCI)

การสำรวจรัฐบาลอิเล็กทรอนิกส์ของสหประชาชาติ (E-Government Survey) เป็นโครงการที่จัดทำขึ้นทุก 2 ปีโดย United Nations Department of Economic and Social Affairs (UN DESA) เริ่มต้นตั้งแต่ปี 2001 การสำรวจนี้มีวัตถุประสงค์เพื่อประเมินสถานะการพัฒนารัฐบาลอิเล็กทรอนิกส์ของ 193 ประเทศสมาชิกสหประชาชาติ โดยมีการจัดทำดัชนีรัฐบาลอิเล็กทรอนิกส์ (E-government development index: EGDI) ซึ่งใช้วัดความก้าวหน้าในระดับประเทศ โดย EGDI เป็นดัชนีรวมที่คำนวณจากค่าเฉลี่ยถ่วงน้ำหนักของดัชนีย่อยที่ผ่านการปรับให้เป็นมาตรฐานแล้ว (normalized indices) 3 ดัชนีย่อย ดังนี้:

<p align="center">รูปภาพที่ 1.1: The three components of the E-Government Development Index (EGDI)</p>

<p align="center">
  <img width="800" alt="EGDI Component" src="https://github.com/user-attachments/assets/f4ec030f-1e14-4059-a32f-ad13691f1d5d" />
</p>

ที่มา: United Nations (2024). UN E-Government Survey 2024. United Nations. https://publicadministration.un.org/egovkb/en-us/Reports/UN-E-Government-Survey-2024 <br/>
<br/>

1. ดัชนีบริการออนไลน์ (Online Service Index: OSI) ซึ่งอ้างอิงจากข้อมูลที่ได้จากการประเมินทางออนไลน์ที่ดำเนินการโดย UN DESA เพื่อตรวจสอบบริการออนไลน์ของประเทศ 193 ประเทศสมาชิกสหประชาชาติ นอกจากนี้ ยังมีการใช้แบบสอบถาม Member State Questionnaire (MSQ) ที่ให้ประเทศสมาชิกตอบ เพื่อเสริมการประเมินด้วย 
2. ดัชนีโครงสร้างพื้นฐานด้านโทรคมนาคม (Telecommunications Infrastructure Index: TII) ซึ่งอ้างอิงจากข้อมูลที่จัดทำโดย International Telecommunications Union (ITU) 
3. ดัชนีทุนมนุษย์ (Human capital Index: HCI) โดยใช้ข้อมูลหลักจาก United Nations Educational, Scientific and cultural Organization (UNESCO)

โดยทั้ง 3 ดัชนีย่อย มีน้ำหนักอย่างละ 1/3
<br/>
<br/>
ผลการจัดทำดัชนีรัฐบาลอิเล็กทรอนิกส์ (EGDI) ประจำปี 2024 ของประเทศ 193 ประเทศ มีรายละเอียดดังนี้

<p align="center">รูปภาพที่ 1.2: Average of EGDI, OSI, TII, and HCI in 2024</p>

![plot1 1_Average](https://github.com/user-attachments/assets/f66d1592-226a-4f14-a253-f718797b722a)

ค่าเฉลี่ย EGDI อยู่ที่ 0.64 โดยดัชนีย่อย TII มีค่าเฉลี่ยสูงสุดที่ 0.69 แสดงถึงประเทศส่วนใหญ่มีความก้าวหน้าด้านโครงสร้างพื้นฐานทางโทรคมนาคมมากกว่าด้านอื่น ในขณะที่ OSI มีค่าเฉลี่ยต่ำสุดที่ 0.58 สะท้อนถึงความท้าทายด้านการให้บริการออนไลน์ ส่วน HCI มีค่าเฉลี่ยอยู่ที่ 0.65 


<p align="center">รูปภาพที่ 1.3: Boxplot of EGDI, OSI, TII, and HCI in 2024</p>

![plot1 2_Boxplot](https://github.com/user-attachments/assets/1a264e47-ca91-4ff5-be9c-e158bbdb761c)

กราฟแสดง Boxplot ของ EGDI, OSI, TII และ HCI ในปี 2024 โดย Boxplot แต่ละอันแสดงค่าต่ำสุด ค่าควอไทล์ที่ 1 ค่า Median ค่าควอไทล์ที่ 3 และค่าสูงสุดของ EGDI และดัชนีย่อย ซึ่งจากกราฟ พบว่า TII มีค่า Median สูงสุด และมีลักษณะเบ้ซ้าย แสดงถึงประเทศส่วนใหญ่มีโครงสร้างพื้นฐานโทรคมนาคมที่พัฒนาในระดับสูง เช่นเดียวกับ HCI ที่มีกราฟมีลักษณะเบ้ซ้ายเช่นกัน ขณะที่ OSI มีค่า Median ต่ำที่สุด และมีค่ากระจายค่อนข้างกว้าง และมี Interquartile Range ค่อนข้างมากกว่าดัชนีย่อยตัวอื่น แสดงถึงค่า OSI ของแต่ละประเทศค่อนข้างห่างกัน





## Comparison of EGDI Across Regions

<p align="center">รูปภาพที่ 1.4: Average EGDI in 2024 by Region</p>

![plot1 4_AveragebyRegion](https://github.com/user-attachments/assets/f14617f1-335a-4ef8-9b97-60a70d5050c2)

กราฟแสดงค่าเฉลี่ย EGDI ในปี 2024 จำแนกตามภูมิภาคต่างๆ 5 ภูมิภาค ได้แก่ แอฟริกา อเมริกา เอเชีย ยุโรป และโอเชียเนีย โดยยุโรป มีค่าเฉลี่ย EGDI สูงที่สุดที่ 0.85 ขณะที่แอฟริกา มีค่าเฉลี่ย EGDI ต่ำที่สุดที่ 0.42


<p align="center">รูปภาพที่ 1.5: EGDI in 2024 by Region</p>

![plot1 5_boxplotbyRegion](https://github.com/user-attachments/assets/19c1b631-6e64-44f0-bab8-b872ec4a596c)

กราฟแสดง Boxplot ของ EGDI ในแต่ละภูมิภาค โดย ยุโรป มีค่า Median สูงที่สุด และมีการกระจายของข้อมูลที่แคบที่สุด แสดงให้เห็นถึงการพัฒนารัฐบาลอิเล็กทรอนิกส์ที่ก้าวหน้าและสม่ำเสมอที่สุด ส่วนแอฟริกา มีค่า Median ต่ำที่สุด และมีการกระจายของข้อมูลค่อนข้างกว้าง แสดงให้เห็นถึงความแตกต่างอย่างมากในการพัฒนารัฐบาลอิเล็กทรอนิกส์ในภูมิภาคนี้ นอกจากนี้ กราฟของแอฟริกายังมีลักษณะเบ้ขวา แสดงถึงประเทศส่วนใหญ่มีการพัฒนารัฐบาลอิเล็กทรอนิกส์ในระดับค่อนข้างต่ำ

<p align="center">รูปภาพที่ 1.6: Percentage of Countries in Each EGDI Group by Region (100% Stacked)</p>

![plot1 6_PercentagebyRegion](https://github.com/user-attachments/assets/9633b384-229f-4f3c-b40f-6e3eaf45d2d5)

กราฟแท่งแสดงร้อยละของ จำนวนประเทศที่อยู่ในกลุ่ม EGDI ในระดับต่างๆ คือ low EGDI, Middle EGDI, High EGDI, Very High EGDI จำแนกตามภูมิภาค โดยยุโรป มีสัดส่วนของประเทศที่อยู่ในกลุ่ม Very High EGDI มากที่สุด คือ 83.7% และไม่มีประเทศที่อยู่ในกลุ่ม low EGDI, Middle EGDI เลย ซึ่งสอดคล้องกับรูปภาพที่ 1.4 และ 1.5 คือ ยุโรปมีความโดดเด่นอย่างชัดเจนในด้านการพัฒนารัฐบาลอิเล็กทรอนิกส์ ขณะที่ เอเชีย มีระดับการพัฒนาที่ค่อนข้างหลากหลาย โดยมีสัดส่วนของประเทศที่อยู่ในกลุ่ม Very High EGDI สูงรองลงมาจากยุโรป คือ 53.2% และมีทั้งประเทศที่อยู่ในกลุ่ม High EGDI และประเทศที่อยู่ในกลุ่ม Middle EGDI ส่วนแอฟริกา มีสัดส่วนประเทศที่อยู่ในกลุ่ม Very High EGDI เพียง 3.7% และมีสัดส่วนของประเทศที่อยู่ในกลุ่ม Low EGDI และ Middle EGDI สูงถึง 13.0% และ 51.9% ตามลำดับ

<p align="center">รูปภาพที่ 1.7: Average EGDI, OSI, TII and HCI in 2024 by Region</p>

![plot1 11_AverageallbyRegion](https://github.com/user-attachments/assets/179ecd71-5c7e-4622-b636-1a846f24a005)

<p align="center">รูปภาพที่ 1.8: EGDI, OSI, TII and HCI in 2024 by Region</p>

![plot1 12_boxplotallbyRegion](https://github.com/user-attachments/assets/d3986fc5-aebb-4f8a-ad03-3c932eeb327a)

รูปภาพที่ 1.7-1.8 แสดงค่าเฉลี่ย และ boxplot ของ EGDI, OSI, TII และ HCI จำแนกตามภูมิภาค ซึ่งผลของดัชนีย่อย OSI, TII และ HCI ค่อนข้างคล้ายกับผล EGDI คือ ยุโรป มีค่าเฉลี่ย และค่า Median สูงที่สุด และแอฟริกา มีค่าเฉลี่ย และค่า Median ต่ำที่สุด ยกเว้น OSI ที่ค่า Median ของโอเชียเนียต่ำกว่าแอฟริกา นอกจากนี้ ยังมีประเด็นอื่นๆ ที่น่าสนใจ เช่น สำหรับแอฟริกา การกระจายของค่า EGDI ภายในภูมิภาค มาจากการกระจายของ TII คือ มีความแตกต่างด้านโครงสร้างพื้นฐานโทรคมนาคมระหว่างประเทศภายในภูมิภาค ขณะที่อเมริกา มีการกระจายทางด้าน OSI หรือด้านบริการภาครัฐที่สูงกว่าดัชนีย่อยอื่น ส่วนยุโรป มีค่า TII ที่โดดเด่นกว่าดัชนีย่อยอื่น และค่อนข้างกระจุกตัวอยู่ในระดับสูง นอกจากนี้ ขณะที่ภูมิภาคอื่นมีค่า TII ที่สูงกว่าดัชนีย่อยอื่น แต่โอเชียเนียกลับมีความโดดเด่นที่ HCI หรือดัชนีทุนมนุษย์ ที่สูงกว่าดัชนีย่อยอื่น





## Comparison of EGDI Across Income Levels

<p align="center">รูปภาพที่ 1.9: Average EGDI in 2024 by Level of Income</p>

![plot1 7_AveragebyIncome](https://github.com/user-attachments/assets/13624067-bd8c-45e7-b307-c232be41ede4)

<p align="center">รูปภาพที่ 1.10: EGDI in 2024 by Level of Income</p>

![plot1 8_boxplotbyIncome](https://github.com/user-attachments/assets/08bfc652-e107-43b5-a598-6217df5561ad)

<p align="center">รูปภาพที่ 1.11: Percentage of countries in each EGDI group by Level of Income (100% Stacked)</p>

![plot1 9_PercentagebyIncome](https://github.com/user-attachments/assets/f0ee9aa2-1c05-4c1d-981b-e7e47d8377b1)

รูปภาพที่ 1.9-1.11 แสดงถึงผล EGDI ของประเทศต่างๆ จำแนกตามระดับรายได้ของประเทศ คือ Low income, Lower-middle income, Upper-middle income และ High income โดยรูปภาพที่ 1.9 เป็นกราฟแสดงค่าเฉลี่ย EGDI ในปี 2024 จำแนกตามระดับรายได้ของประเทศ รูปภาพที่ 1.10 กราฟแสดง Boxplot ของ EGDI จำแนกตามระดับรายได้ของประเทศ และ รูปภาพที่ 1.11 เป็นกราฟแท่งแสดงร้อยละของ จำนวนประเทศที่อยู่ในกลุ่ม EGDI ในระดับต่างๆ คือ low EGDI, Middle EGDI, High EGDI, Very High EGDI จำแนกตามระดับรายได้ของประเทศ 
<br/>
<br/>
ซึ่งจากกราฟทั้ง 3 รูป ค่อนข้างชัดเจนว่าระดับรายได้ของประเทศสัมพันธ์กับคะแนน EGDI โดยประเทศที่อยู่ในกลุ่มรายได้สูงมีโอกาสที่จะมีผลคะแนน EGDI ที่สูงกว่าประเทศที่อยู่ในกลุ่มรายได้ต่ำกว่า

<p align="center">รูปภาพที่ 1.12: Average EGDI, OSI, TII and HCI in 2024 by Level of Income</p>

![plot1 13_AverageallbyIncome](https://github.com/user-attachments/assets/0849d1b2-5dbe-4137-bdbf-33a5641b6d00)

<p align="center">รูปภาพที่ 1.13: EGDI, OSI, TII and HCI in 2024 by Level of Income</p>

![plot1 14_boxplotallbyIncome](https://github.com/user-attachments/assets/9eafab63-7635-4146-8f99-92116163c015)

รูปภาพที่ 1.12 1.13 แสดงค่าเฉลี่ย และ boxplot ของ EGDI, OSI, TII และ HCI จำแนกตามระดับรายได้ของประเทศ ซึ่งผลของดัชนีย่อย OSI, TII และ HCI ค่อนข้างคล้ายกับผล EGDI คือ ระดับรายได้ของประเทศสัมพันธ์กับคะแนนของดัชนีย่อย OSI, TII และ HCI โดยประเทศที่อยู่ในกลุ่มรายได้สูงมีโอกาสที่จะมีผลคะแนนของดัชนีย่อย OSI, TII และ HCI ที่สูงกว่าประเทศที่อยู่ในกลุ่มรายได้ต่ำกว่า






## Relationship between EGDI and OSI, TII and HCI

<p align="center">รูปภาพที่ 1.14: Scatter Plot Matrix of EGDI, OSI, TII, and HCI in 2024 by Level of Income</p>

![plot1 18_pairplotbyIncome](https://github.com/user-attachments/assets/dcbb94fb-945b-4aa0-aea7-1f4f7e336d15)

รูปภาพที่ 1.14 แสดง Scatter Plot Matrix ของ EGDI, OSI, TII, และ HCI โดยแบ่งสีจำแนกตามระดับรายได้ของประเทศ คือ Low income, Lower-middle income, Upper-middle income และ High income ซึ่งผลที่ออกมา ดูเหมือนว่า EGDI, OSI, TII, และ HCI มีความสัมพันธ์กันในระดับสูง 

<p align="center">รูปภาพที่ 1.15: Correlation Matrix of EGDI, OSI, TII, and HCI in 2024</p>

![plot1 17_Correlation_Matrix](https://github.com/user-attachments/assets/99598d15-8ff4-4fe0-8cdd-03006c83c35e)

รูปภาพที่ 1.15 แสดง Correlation Matrix ของ EGDI, OSI, TII, และ HCI ซึ่งผลออกมา คือ ค่า Correlation ระหว่าง EGDI และ OSI, TII, และ HCI อยู่ที่ 0.91, 0.93, 0.93 ตามลำดับ
แสดงถึง EGDI มีความสัมพันธ์กับดัชนีย่อย OSI, TII, และ HCI ในระดับที่สูงมาก นอกจากนี้ ค่า Correlation ระหว่างดัชนีย่อย OSI, TII, และ HCI ยังมีค่าสูงด้วย คือ อยู่ในระดับ 0.73-0.82 แสดงถึง แต่ละดัชนีย่อยก็มีความสัมพันธ์กันเองในระดับสูงด้วย 

<p align="center">รูปภาพที่ 1.16: Linear Regression between EGDI and OSI by Region, Level of Income, EGDI group</p>

![plot1 20_lineOSIbyall](https://github.com/user-attachments/assets/5cf9b12a-f295-410d-a984-028fae70dd88)

<p align="center">รูปภาพที่ 1.17: Linear Regression between EGDI and TII by Region, Level of Income, EGDI group</p>

![plot1 21_lineTIIbyall](https://github.com/user-attachments/assets/554644a0-8e33-4a01-9d61-22ca2dc652ad)

<p align="center">รูปภาพที่ 1.18: Linear Regression between EGDI and HCI by Region, Level of Income, EGDI group</p>

![plot1 22_lineHCIbyall](https://github.com/user-attachments/assets/83368afd-7330-49d4-9214-b35db671a3a0)

รูปภาพที่ 1.16 - 1.18 แสดง Regression Line ระหว่าง EGDI และ OSI, TII และ HCI จำแนกตามภูมิภาค ระดับรายได้ของประเทศ (Low income, Lower-middle income, Upper-middle income และ High income) และกลุ่ม EGDI ซึ่งจากกราฟ พบว่า 
1. Regression Line ระหว่าง EGDI และ OSI, TII และ HCI ที่จำแนกตามภูมิภาค มีความชันของ Regression Line ของแต่ละภูมิภาคใกล้เคียงกัน กล่าวคือ OSI, TII และ HCI ส่งผลต่อ EGDI ของแต่ละภูมิภาคใกล้เคียงกัน
2. Regression Line ระหว่าง EGDI และ OSI, TII และ HCI ที่จำแนกตามระดับรายได้ของประเทศ ความชันของของ Regression Line ของกลุ่มประเทศ Low income น้อยกว่ากลุ่มประเทศอื่น สะท้อนว่า OSI, TII และ HCI ส่งผลต่อ EGDI ในกลุ่มประเทศ Low income น้อยกว่ากลุ่มประเทศอื่น นอกจากนี้ Regression Line ระหว่าง EGDI และ TII ของกลุ่มประเทศ High income มีความชันสูงกว่ากลุ่มประเทศอื่น คือ TII ส่งผลต่อ EGDI ในกลุ่มประเทศ High income มากกว่ากลุ่มประเทศอื่น
3. Regression Line ระหว่าง EGDI และ OSI, TII และ HCI ที่จำแนกตามกลุ่ม EGDI ความชันของของ Regression Line ระหว่าง EGDI และ OSI และ HCI ของกลุ่มประเทศ Low EGDI มีค่าน้อยกว่ากลุ่มอื่น โดยเฉพาะ Regression Line ระหว่าง EGDI และ OSI ที่แทบจะเป็นเส้นตรงขนานกับแกน x คือ OSI แทบไม่มีผลต่อ EGDI เลย ขณะที่ ความชันของของ Regression Line ระหว่าง EGDI และ OSI, TII และ HCI ของกลุ่มประเทศ High EGDI มากกว่ากลุ่มอื่น



<p align="center">รูปภาพที่ 1</p>
<p align="center">รูปภาพที่ 1</p>
<p align="center">รูปภาพที่ 1</p>
<p align="center">รูปภาพที่ 1</p>






![OSI_Thailand_Comparison](https://github.com/user-attachments/assets/db9501c0-a55f-4b4c-a0ec-a573ce3887c0)






# Part 2: How does Thailand perform compared with other countries?

![plot2 0_EGDIandRank](https://github.com/user-attachments/assets/12685ff8-e0b6-4697-9fb0-63296eabe9d7)
![plot2 1_ComparisonEGDI](https://github.com/user-attachments/assets/26521d34-9267-4cf6-b34f-914465b039db)
![plot2 2_EGDIofAllCountries](https://github.com/user-attachments/assets/88923d59-e17a-4c7c-a74c-fa3e6f8cebd2)
![plot2 3_BoxplotEGDIbyAll](https://github.com/user-attachments/assets/0fa93a19-c846-4b69-b0af-7bb0a6d67628)
![plot2 4_ComparisonOSI](https://github.com/user-attachments/assets/37b7dd9d-c10f-43b6-bf86-d84d8d59d82f)
![plot2 5_BoxplotOSIbyAll](https://github.com/user-attachments/assets/669fe7f0-81a4-49e6-b012-6d48cf41efa8)
![plot2 6_ComparisonTII](https://github.com/user-attachments/assets/f57a4f4d-896c-4076-a119-afdca4b3c0b2)
![plot2 7_BoxplotTIIbyAll](https://github.com/user-attachments/assets/c4789d4f-eed7-49dc-befa-fe918282793e)
![plot2 8_ComparisonHCI](https://github.com/user-attachments/assets/b10961c5-bcc3-4e88-99f7-4bbf712bab24)
![plot2 9_BoxplotHCIbyAll](https://github.com/user-attachments/assets/8cf61d53-39bb-4701-a602-3b36086539ff)


# Part 3: Which sub-indices should be prioritized to enhance Thailand's EGDI ranking?

![plot3 1_ComparisonsubOSI](https://github.com/user-attachments/assets/2ba8a7ff-8c03-4166-99b6-4ff3ec409e1c)
![plot3 2_DifferenceMaxOSI](https://github.com/user-attachments/assets/b95b0e8a-772b-4915-a161-78d3086a0253)
![plot3 3_ComparisonsubTII1](https://github.com/user-attachments/assets/5261a5e7-aa26-462a-9829-5783c1edb902)
![plot3 4_ComparisonsubTII2](https://github.com/user-attachments/assets/db843680-81b3-4506-b159-6e57d97ba1a9)
![plot3 5_DifferenceMaxTII](https://github.com/user-attachments/assets/54315a59-d0ee-4209-aff2-a71bfcdb1810)
![plot3 6_ComparisonsubHCI](https://github.com/user-attachments/assets/dfcedc6c-0972-4fe9-a4ce-8dfd65114f16)
![plot3 7_DifferenceMaxHCI](https://github.com/user-attachments/assets/c574ebc5-427e-4601-b662-359d1d0b2ac9)
![plot3 8_EGDITrend](https://github.com/user-attachments/assets/e0bdc709-4e7a-4359-8014-ceb597a4d210)
![plot3 9_EGDIandTarget](https://github.com/user-attachments/assets/612e956a-5c02-45f7-bccb-885e60ef6c26)












