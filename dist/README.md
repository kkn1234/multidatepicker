# Angular multi-date-picker

The project is using existing [MultipleDatePicker](https://github.com/arca-computing/MultipleDatePicker).

In this, you can find addtional features for displaying custom events in calendar based on dates.



### Example

In Html file,
<pre>
	&lt;<span>multiple-date-picker</span> <span>slot-data="calEventData"</span>&gt;
	&lt;<span>/multiple-date-picker</span>&gt;
</pre>

In controller,

$scope.calEventData = [{
"price": 5,
"slotsAvailable" : 3,
"StartDate": "mm-dd-yyyy"
}]

![Screen Shot](https://raw.githubusercontent.com/kkn1234/multidatepicker/master/dist/New%20Picture.bmp)


## Reference

Please read [MultipleDatePicker](https://github.com/arca-computing/MultipleDatePicker) for details on original MultipleDatePicker, installation and examples.


## Author

* **Kiran Kumar KN** - *Added new functionality to existing MultipleDatePicker directive* 

See the original project [MultipleDatePicker](https://github.com/arca-computing/MultipleDatePicker) by arca-computing.


## Acknowledgments

* Credit to arca-computing https://github.com/arca-computing, the orinal author of MultipleDatePicker.

