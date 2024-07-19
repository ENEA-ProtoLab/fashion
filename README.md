# Fashion

Additive Manufacturing in itself has been proved to be a more sustainable mean of production, capable of reduce emissions and material waste. The large pool of 3Ding process present, along with their relative materials, can be easily integrate into the design phases thanks to Computer Design (CD) strategies. Leveraging on GH as its main environment to design, an Interactive Generative Modeling (IGM) tool was developed integrating various way to reach the target. First, it was necessary to investigate practical strategies to customize or apply texture and pattern on any type of 3D shape. These experiments also proved to be a good way to showcase the potentiality of the tool and promote collaborations with CCI and SME. Most importantly, it provides an opportunity to easy access the latest technologies available and helps drive sustainable practices and models in the Fashion sector.
Three case studies were conducted based on the target to establish possible best practices for applying IGM. For the Jewelry sector, which develops specialized software for the sector and boasts links with Trade Associations, several companies inside and outside the region were contacted.
A case study was conducted in the fashion accessories sector with a company that produces buttons for large brands in the clothing sector. The speed of response to the market and product customization represents key elements of production.
For the clothing sector, a case study was conducted with a company that produces embroidery and decorations for large clothing brands. The company's production is characterized by high-quality craftsmanship.

* Case study #1: Jewellery

A first case study was conducted in collaboration with a jewellery studio called Fiabe Gioielli. For this collaboration it was proposed an integration of customization features in the digital modelling of a golden ring with adornment. The customization process consisted of making some open input for the designer, in order to easily iterate different changes whilst remaining consistent with the initial design. This particularly helpful for the creatives of the studio, as it makes possible to quickly change some geometric parameters – such as thickness, width or ring size – as well as explore different designs – like the type of texture and its number of divisions or how much to curve the sections of the geometry. Another point taken into consideration was the final fabrication technique: usually a ring like this is composed of two entities (the ring and the adornment insert), later welded together, mostly for traditional fabrication constrains. By implementing 3D printing as part of the process it was possible to consider the ring as a single entity already welded. Furthermore, there two possible ways to proceed depending on which 3D printing technology chosen: by using PBF such as MBJ or SLM is actually possible to 3D print the final ring directly in gold; otherwise, a more common procedure, is to 3D print a wax model in SLA and use it for investment casting (see chapter 2.3). As for the customization modelling, this difference doesn’t really change too much the strategy (it only means to allow a wider range of thickness).
The CD strategy was developed in GH with the help of the Lunchbox plugin for the generation of the texture. The entire ring was developed inside GH environment without reference to external geometry. This makes each part of the ring completely open to changes, thus requiring particular attention to which parameters to live accessible. The first and most important parameter is the ring size, so every other feature of the ring is re-generated according to it. Other important parameters are the width and the thickness of the ring. For the latest in particular – by the nature of the final design – it was important to understand how each geometry features affects the overall thickness. For the insert part, thanks to Lunchbox plugin, is possible to quickly implement different types of grid-textures and play with its subdivisions number. An important feature to take into account for this part is again the minimum thickness of the grid’s elements, as it needs to be feasible for 3D printing and able to resist to wear.
                 ![image](https://github.com/user-attachments/assets/8144e2ab-4eb9-47f2-b722-ca49c3d2015f)
                             
                           IGM strategy for case study #1 allowing total customization.

   ![image](https://github.com/user-attachments/assets/d991fdef-54fd-4124-bb25-b20b64e2bdb5)
                           
            Different iterations of the golden ring made with the same generative strategy.


Case study #2: Accessories 

The second case study was conducted in collaboration with a button factory of the Bologna district. It was proposed an integration of customization features in the digital modelling of a grumette button. Making some open input for the designer, the customization process allows to easily iterate different changes whilst remaining consistent with the initial design.By using this Grasshopper definition is possible to change some geometric parameters, such as the radius of the button or the dimension of the link of the chain, to reduce or increase the dimension of the button depending on which part of cloth, it will be used on. Regarding the construction process, Polyjet 3D printing can be considered to get the button printed in one piece.
As the previous case study, the entire 3D model is directly built in Grasshopper without external references, allowing to change completely the geometry of the button depending on the features of the GH definition.
The main parameter is the circle of the inner part of the button from which the button itself is generated and every other feature of the button is re-generated according to it. In the GH definition of this case study, two plug in where mainly used: Pufferfish and Pancake. The first one was used because there are in it some parameters and factors for inputs for more custom control. Pancake includes, among other things, components for JSON-like structure manipulation and JSON/XML export/import support.  

![image](https://github.com/user-attachments/assets/06f7cf58-7776-4e6b-a4bb-2093b24d0a6d)
![image](https://github.com/user-attachments/assets/cdb92d1a-8749-48cd-96de-078c08a70299)






