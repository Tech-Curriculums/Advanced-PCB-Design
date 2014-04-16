## EDN Design 

4 minutes

http://www.edn.com/design/components-and-packaging/4390811/PCB-layout-considerations-for-non-isolated-switching-power-supplies

![img](http://m.eet.com/media/1167630/pcb_layout_considerations_for_switching_power_supplies_fig1.jpg)


things to look out for:

1. thermal stress
2.  noise and interactions among traces and components
3.  voltage drop
4.  transients


Sandwiching with GND layers:

small signal layers can be on the middle layers in order to reduce coupling to the outer layers (basically it will ensure that we will dynamically modify the charge concentration in order to reduce the higher fourier components from affecting the Power line  -- which could potentially interfere with other modules, depending on how well their voltage regulation is going).


> Finally, it is also desirable to have thick copper for the external high current power layers to minimize the PCB conduction loss and thermal impedance.


