# WAB_Select-PermitParkingCalculator-Widget
Select Widget for Permit Parking Calculator (https://wspdsmap.cityoftacoma.org/website/PW/ParkingCalculator2/).

Customization to make interface more intuitive.

Version 2.12

INSTRUCTIONS:
1. Copy Widget.html to \widgets\Select\Widget.html


Future Enhancements: 
      * Hide checkboxes in \widgets\Select\css\style.scss 
        example - .jimu-widget-select display: none;)
      * Hide extra map layers in Widget.js within the _initLayers function
        example - if(layerObject && layerObject.objectIdField && layerInfoArray[index].id != 'Tacoma City Boundary' && layerInfoArray[index].id != 'Neighborhood Business Districts') {

