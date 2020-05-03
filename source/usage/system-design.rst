System Design
=============
.. toctree::
   :maxdepth: 3

The design of the system is the last step before we get to the point of analysis and report of the system as we have
defined it. In the System Design part the software offers Sizing Summary, Electrical Configuration, Tracking and
Orientation, Electrical sizing information and AC Sizing.

This section has parameters that the user needs to enter some basic system configurations. In this section, some
dependencies are formed in the system.

Capacity from PV systems may be measured by either their AC or DC capacity. PV
modules produce direct current (DC) voltage. This DC electricity is converted into alternating current (AC). As a
result, PV power plants have both a DC rating (corresponding to the output of the modules) and an AC rating, which
is always lower than the DC rating because of losses associated with converting DC to AC.

Inverters operate within a specific input voltage range, called the operating range. Panel strings must output a
voltage that falls within that range.

**Array** - is the complete physical assembly of PV modules. In a hierarchical sense, arrays are composed of
sub-arrays. Each sub-array is composed of PV modules in close physical proximity and with the same orientation.

**String** – is an electrical concept. A series-connection of identical PV modules. The current in a PV string is
equal though each module, while the overall voltage of a string is the sum of the individual voltages of each module.

**Sub-array** – is a portion of the total PV array that is physically co-located and oriented in the same direction.
Each module in a sub-array should have the same sun intensity and should have the same electrical characteristics.
For this reason, all of the modules in a string should also be composed of modules in the same sub-array - to the
greatest extent possible.

**Strings in parallel in sub-array**- With parallel connected modules, each string to be connected in parallel should
have its own blocking diode. This not only reduces the required current carrying capability of the blocking diode,
but also prevents current flowing from one parallel string into a lower-current string and therefore helps to
minimize mismatch losses arising in parallel connected arrays.

**Voc** - module rated open current voltage [V]. Found on module data sheet.

**Vmp** - rated module max power voltage [V]. Found on module data sheet.

**Tilt Angle** is the angle between the horizontal plane and the solar panel at which can be set or adjusted to
maximize seasonal or annual energy collection.

**Azimuth angle** is the compass direction from which the sunlight is coming.

**Maximum DC voltage** is a safety relevant limit for sizing a PV system.

**MPPT** or Maximum Power Point Tracking is an algorithm that is included in charge controllers used for extracting
maximum/minimum available power from PV modules under certain conditions. The voltage at which PV module can produce
maximum/minimum power is called maximum/minimum power point. Maximum/minimum power varies with solar radiation,
ambient temperature and solar cell temperature.



