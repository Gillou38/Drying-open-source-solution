Open Source Vegetable Dryer
===========================

-   A vegetable dryer 

-   Combines solar and electrical energies

-   Designed for professional farmers

-   Scalable and autonomous

Motivation
----------

### Why this project?

This project is dedicated to farmers needing drying solutions for their
vegetables, aromatic or medicinal plants, fruits or other kinds of products. The
drying process allows farmers spreading their outcome beyond the harvest season
and therefore to secure a stable revenue over the year.

### Why open source?

We concur with the idea that open source and DIY farming tools support technical
independence, which is a critical issue for farmers. Therefore, dryer we want to
develop here is aimed to be open source, to be produced indifferently in DIY or
industrial production settings, and to be easily repaired. we are committed to
provide technical solutions with sufficient documentation securing the four
freedoms of open source:

-   Freedom to study: the right to access enough information to understand how
    the piece of hardware (referred herein as the product) works and to retrace
    the logic behind its design;

-   Freedom to modify: the right to edit the product definition documents and to
    tweak or develop the product further for any purpose;

-   Freedom to make: the right to use the product definition documents to
    manufacture the piece of hardware;


-   Freedom to distribute: the right to share or sell the product definition
    documents as well as the physical products fabricated according to these
    documents.

The documentation shared in this repository is licensed under a [GNU GPL v3
license](http://www.gnu.de/documents/gpl.en.html). Designs are licensed under a
[CERN Open Hardware Licence
V1.2](https://www.ohwr.org/licenses/cern-ohl/license_versions/v1.2).

### How to contribute

Every bit of help is more than welcomed. If you want to support the project,
promote it or concretely participate in the development, have a look at our
[Contribution
guide](https://github.com/Gillou38/Drying-open-source-solution/blob/master/Contribution%20guide.md)!

About dry-ing and -ers
----------------------

Drying is one of the most efficient food conservation methods. It helps keeping
a great share of nutriment, reduces the weight and the volume of food products
and enables long warehousing duration. It is a physicochemical reaction, whose
aim is to extract water out of something. Professional alimentary applications
requires dealing with conflicting constraints of high processing speed and
keeping control on the reaction in order to conserve valuable nutriments.

### History
That technic begins with the beginning of the agriculture, around 12 000 B. C. by inhabitants of the modern Middle East and Asia region. In beginning drying was realize by evaporation (air drying, sun drying ...). With time and technical evolution, there's actually a lot of different technic to dry food, from very low tech solution to high tech solution (we exclude freezing drying, because it's a very different process).

In drying, there is no “one-size-fits-all”-solution. Each farmer may need a very
specific solution fitting their specific requirements regarding size and
temperature range for example. The objective of the project is therefore to
develop a scalable and modular dryer which can be adapted to each specific
situation. Doing so, we want also to provide documentation about drying which
can be easily accessible to farmers.

### Composition of a dryer

A dryer is composed of:

-   a drying room, whose aim is to host the food products to be dried and to put
    their surface in contact with a dry and heated airflow. The role of the air
    flow is to capture the water contained in the food products while getting in
    contact with their surface. In order to maximise the contact surface, a good
    solution is to use trays helping to distribute the products and let the
    airflow circulating around them. Trays are generally made of food-safe
    screens and frameworks. For drying aromatic and medicinal plants, there are
    generally two ways to distribute products on the trays: the “thin layer”-way
    with only one layer of product on each tray, and the “thick layer”-way with
    around 10 to 15 centimetres of products on each tray.

-   a heating system, which can either be solar (direct or indirect), electrical
    or fuelled by biomass or combustion.

-   an air flow drying system, which can be either based on air exchange,
    condensation or absorption.

-   a convection system to convey the dry air flow through the drying room. The
    choice of the convection system depends on the product to be dried, the
    expected drying time and the thickness of the food's layer. It can be either
    natural or forced.

-   optionally a thermal inertia system, helping dryers whose heating system
    can't operate all day long (like solar systems) to stock energy.

Basic dryers tend to combine functions such as drying and heating into one
component and to use wind to create ventilation. More advanced solutions use one
component for each function.

Our design rationale
--------------------
We intend to use low tech and low energy consumption solutions whenever it is
possible. The current development focuses on a solar solution with electrical
assistance and regulation which enable professional users to process food
products regardless of the daytime (that is, even when there is no sunlight).
