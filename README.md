# Dryer-open-source-solution
Develop a dietary dryer, which can articulate solar and electrical energy. Preferring develop for professional farmer to get liberty and technical autonomy.

## Project presentation
### Why this project?
This project is an help for each producer of vegetables, plants, fruits or other kinds of food goods who wants to transform his/her product with an effective drying solution.

Very useful for production of aromatic or medicinal plants, the dryer is a source of freedom for the producers : thez can organize themself the food processing and selling according to the seasonal variations.

It can be use, by fruits, vegetables and plants producers, to transform and valorise a lot of kinds of product and it could be an opportunity to diversify his/her production (dry tisane, apples, tomatoes ...).

### Why open source?
Today, for a farmer, his/her technical dependence can be a real problem to have a stable life. That's why, we're positioning us to develope the farmer autonomy by the knowledge and the know-how about the farm's tools, and especially the dryer. So that product need to be make simply by DIY, or by industrial process and let free the farmer to optimize, modify or repair his/her product like he/she wants.

We try to document design process to let people join the group easily, and to educate peoples to understand how a product is designing from A to Z. 

With open source logic, there's necessary documentation, which explain, how the product works and how it can be made. In order to conserve the four fundamental liberty of open source:
- Freedom to study: the right to access enough information to understand how the piece of hardware (referred herein as the product) works and to retrace the logic behind its design;
- Freedom to modify: the right to edit the product definition documents and to tweak or develop the product further for any purpose;
- Freedom to make: the right to use the product definition documents to manufacture the piece of hardware;
- Freedom to distribute: the right to share or sell the product definition documents as well as the physical products fabricated according to these documents.

For our application, we chose to protect all our documentation production by a GNU GPL v3, and our design production by a CERN Open Hardware Licence V1.2.

### Where we want to go?
We want to develop a scaling method to let the producer to make his own dryer, adapted for his utilisation, and in his/her infrastructure. All of that to maintain and improve the producer's autonomy.

So by developing a standard dryer, we want to expand it to a group of solution, and make generic frame ready to be modifies in an infinity of solutions adapted to each producer.

Coupled with that, we want to organise information and test dryer, to create a data base with lot of organised information around drying, easy to reach.

### How to contribute
Everybody can help, just by supporting the project, by promotting it or by helping to develop the project. 

Even if you don't know how you can help, you can come with us to learn how to design a product, what's the classic process. We try to set a learning method up, with explication of what we do.

For most precise description, see [Contribution guide](https://github.com/Gillou38/Drying-open-source-solution/blob/master/Contribution%20guide.md).

## Drying 
It's a physicochemical reaction, which extract water of something. For dietary application, the reaction need to be control to conserve nutriment, but for a professional, the reaction need to be fast. So in our development, we try to mix that 2 constraints, to optimize the process.

Drying is the 1st method use to conserve food, because that transformation keeps a good concentration of nutriment, and reduce weight and volume.

### History
That technic begins with the beginning of the agriculture, around 12 000 B. C. by inhabitants of the modern Middle East and Asia region. In beginning drying was realize by evaporation (air drying, sun drying ...). With time and technical evolution, there's actually a lot of different technic to dry food, from very low tech solution to high tech solution (we exclude freezing drying, because it's a very different process).

### Composition of a dryer
A dryer is composing of a drying room, where food can be stocked and dispose to be dried. In that room, there is a dry airflow, by natural or forced convection, which flow around food to capture water present in the food. 

For the more basic dryer, the drying room is the heating component, and the ventilation is make by wind, so all of the product is in only one room.

For more complex solutions, there's one system for each component.

### The components
For each solution, there the same kind of component, sometimes together in the same object, sometimes separate in different modules. (See state of art, for more precision)

Quickly, we're defining the different components of a dryer, and the different technologies used.

#### Drying room
The drying room is the room where food will be dry. For this component, we need to make a state of art of dietary material.

- The trays

To have a good drying, the drying room, need to have trays to distribute the product to be dried, and let the airflow circulate around product. Generally, that trays are composed of food safe screens and frameworks.

#### Heat system
- Solar (direct, indirect)
- Electrical
- Warm and pollute flow (biomass, wood combustion, oil ...) => heat exchangeur

##### Thermal Inertia system
  
For heat system which can't heat all the day, like solar system, is possible to couple it with a inertial system, which can stock energy for the night.

#### Convection system
The choice of the convection depend of the product to be dried, the speed of the drying and the thickness of the food's layer 
- Natural: work with rising warm airflow 
- Forced: work with an system which create airflow. For aromatic and medicinal plants, two kind of sizing of the system can be identified, to dry:
  - Fine layer: only one layer of product on the trays
  - Thick layer: around 10 or 15 centimeters of product on the trays

#### Air flow drying system:
- Air exchange
- Condensation
- Absorption

### Our position
We want to use at best low tech and low energy consummation solution when that is possible, and use other efficient solution when we need. Actually, we orient the development around a solar solution with electrical assistance and regulation which let free a professional producer to dry his/her production when he/she want, even if solar energy isn't optimal.

## Nutriment saving
A lot of study is realised around quality of food, and conservation of nutriment during transformation. Another secondary goal is to optimise and document how technical choice change the nutriment conservation.
