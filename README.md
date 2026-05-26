# SP Thesis
Topic: Predictive Model of Microhardness in Laser Cladding Process Followed with Deep Rolling Process of UIC860 Grade 900A Rail Using Machine Learning Technique

# Material
- Rail : UIC860 Grade900A
- Coating : Colmonoy 63

# Input Data 
- Deep rolling (DR) Parameter : DR Pressure, Rolling offset, Feed rate
- Microhardness Indentation Depth (50,100,150,200,250)
- surface roughness (SA) : 
  area 10 x 40 mm
- **** Image Microstructure (Pores, Dendritic Density) differenct zoom level e.g. 300x, 700x, 1000x
# Output Data 
Microhardness 
3 zone : clad Layer (AVG 4 data), Interface (AVG 4 data), substrate (AVG 2 data)

# จำนวน speciment 
- 54 speiment (มาจาก 27 การทดลอง 2 ซ้ำ)
# ML Technique
- Deeptab: Tabular Deep Learning Made Simple
** ต้องทำรูปให้เป็น Column ก่อน **
