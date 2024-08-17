The load cell gain can be easily measured. The procedure is as follow:

1.First, initialize the module and set the scaling factor to 1 (set_scale()).  
2.Then, tare the scale (tare_all()).  
3.Once the module has been correctly initialized, measure a known weight and note the value obtained from the HX711 module.  
4.Divide this value by the real value. The result is the parameter you need to pass to set_scale.  
