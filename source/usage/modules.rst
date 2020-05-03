Modules
=======

.. toctree::
   :maxdepth: 3

The system has a full database of PV modules with their appropriate specifications. The user has the option of
selecting the appropriate module that he / she will be using. The user can search the database by Name, Technology,
Bifaciality, Maximum Power, Temperature Coefficient and Module Area.

-- modules image --

The physical and additional parameters of the module are provided with the module itself being pre-defined according
to the module specification from the database.

If there is a need for a specification of a component that does not exist in the database the client should contact
support with the name and specification of the component so it will be added to the database.

By selecting the desired PV module from the table, the user has defined the module that will be used for the
simulation and can continue to the next step.

In the models section when selecting the appropriate base module there are predefined parameters according to which
the choice of the desired module can be made.

The following parameters are describing one module in the database:

**Module name** that describes the module of the appropriate type and manufacturer.

**Technology** that uses the selected module.

.. note::
    Here we have monocrystalline solar panels that are generally thought of as a premium solar product. The main
    advantages of monocrystalline panels are higher efficiencies and sleeker aesthetics.

    Polycrystalline solar panels generally have lower efficiencies than monocrystalline options, but their advantage is a
    lower price point. Polycrystalline solar panels are also made from silicon.

    CIS stands for the elements copper (C), indium (I) and selenium (S), which are the materials on which CIS technology
    is based. The higher energy yield compared with conventional crystalline silicon modules is one of a number of
    significant advantages.

    There are three main types of thin-film solar cells, depending on the type of semiconductor used:
    amorphous silicon (a-Si), cadmium telluride (CdTe) and copper indium gallium diselenide (CIGS).
    Cadmium telluride (CdTe) photovoltaics describes a photovoltaic (PV) technology that is based on the use of
    cadmium telluride, a thin semiconductor layer designed to absorb and convert sunlight into electricity.

    The benefits of CdTe thin-film solar cells include: High absorption - Cadmium telluride is a direct-bandgap
    material with band gap energy of about 1.45 defined (eV), which is well matched to the solar spectrum and nearly
    optimal for converting sunlight into electricity using a single junction. Low-cost manufacturing - Cadmium telluride
    solar cells use low-cost manufacturing technology to produce low-cost cells.

    Copper indium gallium selenide solar cell (or CIGS cell, sometimes CI(G)S or CIS cell) is a thin-film solar cell used
    to convert sunlight into electric power. It is manufactured by depositing a thin layer of copper, indium, gallium and
    selenium on glass or plastic backing, along with electrodes on the front and back to collect current. Because
    the material has a high absorption coefficient and strongly absorbs sunlight, a much thinner film is required
    than other semiconductor materials.

    Amorphous silicon (a-Si or a-Si:H) solar cells belong to the category of silicon thin-film, where one or several
    layers of photovoltaic material are deposited onto a substrate. Disadvantage is that amorphous thin-film solar
    cells have lower efficiency rates.

**Bifacial** modules

Bifacial solar panels are types of panels that have solar cells on both sides. This enables the panels to absorb
light from the back as well as the front. This means that a bifacial solar panel can absorb light that is reflected
off the ground or another material. One of the most noticeable physical traits of bifacial panels is their slim
profile – many bifacial designs call for limited framing, and the modules themselves are housed in a thin,
transparent layer which can be a dual-glass design or made with a clear back sheet.

**Maximum power** is the product of the module efficiency, irradiance at standard test conditions (1,000 W/m2), and
the module area. Where module efficiency is a measurement of a solar panel’s ability to convert sunlight into usable
electricity. Given the same amount of sunlight shining for the same duration of time on two solar panels with
different efficiency ratings, the more efficient panel will produce more electricity than the less efficient panel.
The module efficiency is given by percentage. And the other parameter irradiance is the power per unit area (watt per
square meter, W/m2), received from the sun in the form of electromagnetic radiation as reported in the wavelength
range of the measuring instrument.

**Temperature coefficient** of power indicates how strongly the PV array power output depends on the cell temperature,
meaning the surface temperature of the PV array. It is a negative number because power output decreases with
increasing cell temperature.

**Module Area** is a parameter of a module that is a measure of the module's "size". These parameters describe the
physical properties of the module selected.

These are the parameters according to which we can select the required module from the database.
When the module is selected, the overview of the ordered features that the corresponding module has already been selected.
In the section of physical characteristics are inserted and they describe the basic external features of the module.


**Module width, Module Height** are parameters of a module that are a measure of the module's "size".
These parameters describe the physical properties of the module selected.

**Number Of Cells** - Photovoltaic cells are the component of a solar panel that converts sunlight into electricity.
When sunlight hits the silicon, electrons in the cell are energized and begin to move, initiating a flow of electricity.
A single solar cell isn’t going to produce much electricity; that’s why they’re grouped together in solar panel modules.

Additional characteristics include features that describe module specifications and durability.

**T-noct** - Nominal Operating Cell Temperature is the temperature of each panel at an irradiance of 800 W/m2 and an
ambient air temperature of 20°C and wind speed is 1 m/s at a module tilt angle 45°C. NOCT is a very critical
parameter that is required by various performance, qualification and energy rating standards/methods. It can be used
with the maximum power temperature coefficient to get a better real-world estimate of power loss due to temperature
increase.

**A_ref** – Ideality factor of a diode is a measure of how closely the diode follows the ideal diode equation. The
derivation of the simple diode equation uses certain assumptions about the cell. In practice, there are second order
effects so that the diode does not follow the simple diode equation and the ideality factor provides a way of
describing them.

**I_L_ref** – Light generated current is the generation of current in a solar cell.

**I_o_ref** – Saturation current is the maximum current which can be obtained under certain conditions.

**R_f**- Series resistance in a solar cell has three causes: firstly, the movement of current through the emitter and
base of the solar cell; secondly, the contact resistance between the metal contact and the silicon; and finally, the
resistance of the top and rear metal contacts. The main impact of series resistance is to reduce the fill factor,
although excessively high values may also reduce the short-circuit current.

**R_sh_ref** - Shunt resistance causes power losses in solar cells by providing an alternate current path for the
light-generated current.

**Nominal efficiency** - is defined as the ratio of energy output from the solar cell to input energy from the sun.

**Max power voltage** - is the voltage when the power output is the greatest. It is the actual voltage you want to see
when it is connected to the Maximum Power Point Tracking (MPPT) solar equipment under standard test conditions.

**Max power current** - is the current when the power output is the greatest. It is the actual amperage you want to
see when it is connected to the Maximum Power Point Tracking (MPPT) solar equipment under standard test conditions.

**Open circuit voltage** - is how many volts the solar panel outputs with no load on it.

**Short circuit current** - is how many amps (i.e. current) the solar panels are producing when not connected to a
load but when the plus and minus of the panel wires are directly connected to each other.

**Mounting configuration** - Photovoltaic mounting systems (also called solar module racking) are used to fix solar
panels on surfaces like roofs, building facades, or the ground.