**cat intrusiondetection.yang**

![cat_intrusiondetection_yang1](cat_intrusiondetection_yang1.png)

![cat_intrusiondetection_yang2](cat_intrusiondetection_yang2.png)

![cat_intrusiondetection_yang3](cat_intrusiondetection_yang3.png)

**pyang -f yin -o intrusiondetection.yin intrusiondetection.yang**

![pyang_intrusiondetection](pyang_intrusiondetection.png)

**cat intrusiondetection.yin**

![cat_intrusiondetection_yin1](cat_intrusiondetection_yin1.png)

![cat_intrusiondetection_yin2](cat_intrusiondetection_yin2.png)

![cat_intrusiondetection_yin3](cat_intrusiondetection_yin3.png)

**pyang -f uml -o intrusiondetection.uml**

![pyang_intrusiondetection_uml](pyang_intrusiondetection_uml.png)

**cat intrusiondetection.uml**

![cat_intrusiondetection_uml](cat_intrusiondetection_uml.png)

**python3 -m plantuml intrusiondetection.uml**

![python_plant_uml](python_plant_uml.png)
